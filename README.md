# javascriptmasterclass

# Instruções
 
## Slides
Os slides das aulas estão disponíveis junto ao conteúdo de cada uma das aulas.

## Exemplos
Os exemplos implementados nas aulas também estão disponíveis para download junto ao conteúdo de cada aula.

## Exercícios

Ao longo do treinamento vamos construir, passo a passo, um gerenciador de banco de dados, ou SGBD, com suporte para a linguagem SQL.

O objetivo será disponibilizar os seguintes comandos:

### CREATE TABLE
create table author (id number, name string, age number, city string, state string, country string)


### INSERT
insert into author (id, name, age) values (1, Douglas Crockford, 62)


### SELECT
select name, age, city from author where age > 50 and age < 60


### UPDATE
update author set age = 45 where id = 2


### DELETE
delete from author where age < 50

Não se preocupe pois no conteúdo de cada exercício estarão as instruções para a implementação, além de dicas de como atingir o resultado. As aulas de correção dos exercícios estarão disponíveis a partir de 23/12.


## Configuração do Ambiente

Vamos precisar do Node.js instalado, de preferência na última versão. Você pode entrar no link abaixo, fazer o download e seguir as instruções de instalação para o seu sistema operacional:

https://nodejs.org/

Além disso, você vai precisar de um editor e eu sugiro o Visual Studio Code, mas você pode utilizar algum outro da sua preferência. Segue abaixo o link para download:

https://code.visualstudio.com/