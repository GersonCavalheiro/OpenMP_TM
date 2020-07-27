# Implementação OpenMP para memórias transacionais (experimental)

## O que há por aqui?
Arquivos C++ com as (pseudo) implementações em OpenMP utilizando a biblioteca TinySTM e GCC-TM para controlar o acesso a variáveis dentro das regiões paralelas

Fontes disponíveis em no diretório cowichan/cowichan_openmpTM e cowichan/cowichan_openmpTiny 

### Problemas Cowichan
Implementações disponíveis do diretório **cowichan/cowichan_openmpTM** e **cowichan/cowichan_openmpTiny**.

#### Benchmarks com implementação realizada:
- hull
- norm
- outer
- sor
- thresh
- vecdiff

#### Fontes originais do cowichan:
Disponível em: https://code.google.com/archive/p/cowichan/

Obs.: analisar demais benchmarks, pois a princípio não há necessidade de implementação
