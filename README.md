# Estudo de caso: Ingresso de Pessoas Negras no ensino superior no Brasil antes e depois das cotas raciais

## Motivação

As cotas raciais impactaram no número de pessoas negras nas universidades. Partindo deste ponto: como um algoritmo para definir quem entra na universidade ou não, atuaria com as bases de dados antes e depois das cotas raciais no Brasil?

A abordagem será analisar dois datasets: um de um período antes da implantação das cotas raciais e outro período após as cotas raciais. E com isso:

1. Tirar conclusões sobre datasets influenciados pela variável racismo podem afetar o resultado de um algoritmo.

2. Propor abordagens para utilização de tais algoritmos sobre datasets como estes que não potencializem opressões já existentes.

## Dataset

Dados no http://portal.inep.gov.br/web/guest/microdados

*Os dados sobre o Curso Superior começam a ter o campo raça/cor a partir de 2007.*

Periodos:
> 2016 e ?

2016, após baixar os dados do período de 2016, você encontrará na pasta:
> ANEXOS/ANEXO 1 - Dicionario de dados e tabelas auxiliares/Dicionário de Dados.xls

> DADOS/DM_ALUNO.csv

> Tamanho: ~5GB

## Executar o Jupyter notebook

Com Docker:

Com Docker:
- Cole o arquivo `.CSV` dentro da pasta `DATA`.
- Vá para o terminal, entre na pasta do projeto e execute o comando abaixo.
  ```SH
  docker run --rm -it -v `pwd`:/home/jovyan/work -p 8888:8888 jupyter/datascience-notebook jupyter notebook
  ```
- Será gerado uma mensagem como no exemplo abaixo, substitua os valores `http://(b41990cc3348 or 127.0.0.1)` por `localhost` e cole no navegador para abrir o jupter.
  ```SH
  Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://(b41990cc3348 or 127.0.0.1):8888/?token=154899aebefe13fddac3d9f63f2943b030fcfbc00db5d7fc
  ```
- Na imagem abaixo vá em `new -> Python 3` e inicie suas análises com o Jupyter.
  ![imagem do jupter](./DATA/jupyter.png)