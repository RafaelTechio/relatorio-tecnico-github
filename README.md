# Relatório Técnico Github

Rafael Mateus Zimmer Techio - Engenharia de Software - Módulo 5 - Semana 1

## Introdução

O git é um sistema de gerenciamento de arquivos que suporta versionamento e histórico de alterações e por sua facilidade e rapidez é usado em todo o mundo para desenvolvimento de software em áreas pessoais, academicas e profissionais. Relacionado com ele, há o github, que usa o git para versionar os arquivos mas adiciona uma série de features e estrutura como armazenamento próprio, sendo um hub utilizado por boa parte da comunidade de software.

## Objetivo

Esse relatório técnico tem como objetivo documentar passo a passo as sessões de tutorial de github do site w3schools, de Get Started até Push to Branch. O link para visualizar as sessões pode ser acessado [aqui](https://www.w3schools.com/git/git_remote_getstarted.asp?remote=github).

## Desenvolvimento

### Get Started
Para começar, foi necessário acessar minha conta github relacionada ao inteli e criar um novo repositório.

_Imagem aqui_

Seguindo o tutorial, é pedido que usemos o comando ```git remote add origin _url https do repositório_``` mas esse comando apenas funciona se a pasta atual do terminal já tem um repositório incializado. Portanto, deve ser usado assim:

_Imagem aqui_

Após isso, o tutorial pede para que façamos push da branch master. O comando funcionou, mas a padronização da branch principal hoje é main, e não master, por conta disso foi criada uma nova branch. Para garantir a fidelidade com o tutorial, irei continuar usando a master como principal.

_imagem aqui_

### Github Edit Code

O github permite a edição de arquivos como readme em seu site. Para tal, basta clicar no ícone de lápis, editar e clicar no botão de commitar, editando as informações caso desejar.

_imagem aqui_

### Pull from Github

Nessa sessão, aprendi que o git pull é um comando feito por outros dois: o ```git fetch``` e o ```git merge```
A seguir, imagens de como os comandos funcionam, usando o ```git status``` para avaliar:

_imagem aqui_

Usando o ```git pull origin```:

_imagem aqui_

### Git Push to Github

Agora, iremos enviar as mudanças locais até o repositório usando ```git push``` e aprendendo a usar o commit.

_imagem aqui_

### Git GitHub Branch

Nessa parte, iremos criar uma nova branch através do github:

_imagem aqui_


### Git Pull Branch from GitHub

Agora, iremos aprender como atualizar outras branchs no repositório local. Para isso, iremos usar os comandos ```git pull``` para atualizar ```git branch``` para listar as branchs e ```git checkout _branch name_``` para mudar de branch.

_imagem aqui_

### Git Push Branch to GitHub

Nessa sessão, iremos criar uma branch nova:

_imagem aqui_

Subir algumas alterações:

_imagem aqui_

E então fazer o pull request, levando as alterações da branch update-readme para a branch-test

_imagem aqui_

## Resultados

Como resultado após a realização dos tutoriais, pude reforçar os comandos básicos e a lógica de git: como criar um repositório, gerenciar seus arquivos, criar commits, gerenciar branchs e mergea-las.

## Conclusão

O uso do github é benéfico para o dia a dia da área de programação pois permite uma série de funcionalidades como versionamento, histórico, co-programing e mais.
