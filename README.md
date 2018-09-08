# Estudo de caso: Ingresso de Pessoas Negras no ensino superior no Brasil antes e depois das cotas raciais

Dados no http://portal.inep.gov.br/web/guest/microdados

*Os dados sobre o Curso Superior começam a ter o campo raça/cor a partir de 2007.*

Periodos:
> 2016 e ?

2016, após baixar os dados do período de 2016, você encontrará na pasta:
> ANEXOS/ANEXO 1 - Dicionario de dados e tabelas auxiliares/Dicionário de Dados.xls
> DADOS/DM_ALUNO.csv
> Tamanho: ~5GB

# Executar o Jupyter notebook

With Docker:

`docker build -t inep-curso-superior`

`docker run --rm -it -p 8888:8888 -v "$(pwd):/notebooks" inep-curso-superior /bin/bash`
