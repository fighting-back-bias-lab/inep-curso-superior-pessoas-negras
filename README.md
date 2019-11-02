# Estudo de caso: Ingresso de Pessoas Negras no ensino superior no Brasil antes e depois das cotas raciais

## Motivação

As cotas raciais impactaram no número de pessoas negras nas universidades. Partindo deste ponto: como um algoritmo para definir quem entra na universidade ou não, atuaria com as bases de dados antes e depois das cotas raciais no Brasil?

A abordagem será analisar dois datasets: um de um período antes da implantação das cotas raciais e outro período após as cotas raciais. E com isso:

1. Tirar conclusões sobre datasets influenciados pela variável racismo podem afetar o resultado de um algoritmo.

2. Propor abordagens para utilização de tais algoritmos sobre datasets como estes que não potencializem opressões já existentes.

## Wiki

Aqui vc encontra informações gerais sobre a base de dados e como executar o projeto utilizando o Jupyter Notebook:  https://github.com/fighting-back-bias-lab/inep-curso-superior-pessoas-negras/wiki/P%C3%A1gina-principal

## Dataset

Dados no http://portal.inep.gov.br/web/guest/microdados

## Com Docker:
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

## Quadro de atividades

No quadro em estilo Kanban https://github.com/fighting-back-bias-lab/inep-curso-superior-pessoas-negras/projects/1 se encontra os status das issues e a(s) pessoa(s) responsáveis.
