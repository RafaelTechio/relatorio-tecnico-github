# Relatório Técnico Github

Rafael Mateus Zimmer Techio - Engenharia de Software - Módulo 5 - Semana 1

## Introdução

O git é um sistema de gerenciamento de arquivos que suporta versionamento e histórico de alterações e por sua facilidade e rapidez é usado em todo o mundo para desenvolvimento de software em áreas pessoais, academicas e profissionais. Relacionado com ele, há o github, que usa o git para versionar os arquivos mas adiciona uma série de features e estrutura como armazenamento próprio, sendo um hub utilizado por boa parte da comunidade de software.

## Objetivo

Esse relatório técnico tem como objetivo documentar passo a passo as seções de tutorial de github do site w3schools, de Get Started até Push to Branch. O link para visualizar as seções pode ser acessado [aqui](https://www.w3schools.com/git/git_remote_getstarted.asp?remote=github).

## Desenvolvimento

### Get Started
Para começar, foi necessário acessar minha conta github relacionada ao inteli e criar um novo repositório.
![imagem 1](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/1.png)
![imagem 2](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/2.png)
![imagem 3](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/3.png)


Seguindo o tutorial, é pedido que usemos o comando ```git remote add origin _url https do repositório_``` mas esse comando apenas funciona se a pasta atual do terminal já tem um repositório incializado. Portanto, deve ser usado assim:

![imagem 4](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/4.png)
![imagem 5](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/5.png)
![imagem 6](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/6.png)

Após isso, o tutorial pede para que façamos push da branch master. O comando funcionou, mas a padronização da branch principal hoje é main, e não master, por conta disso foi criada uma nova branch. Para garantir a fidelidade com o tutorial, irei continuar usando a master como principal.

![imagem 7](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/7.png)
![imagem 8](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/8.png)
![imagem 9](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/9.png)


### Github Edit Code

O github permite a edição de arquivos como readme em seu site. Para tal, basta clicar no ícone de lápis, editar e clicar no botão de commitar, editando as informações caso desejar.

![imagem 10](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/10.png)
![imagem 11](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/11.png)
![imagem 12](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/12.png)

### Pull from Github

Nessa seção, aprendi que o git pull é um comando feito por outros dois: o ```git fetch``` e o ```git merge```
A seguir, imagens de como os comandos funcionam, usando o ```git status``` para avaliar:

![imagem 13](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/13.png)
![imagem 14](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/14.png)
![imagem 15](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/15.png)
![imagem 16](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/16.png)

Usando o ```git pull origin```:

![imagem 17](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/17.png)
![imagem 18](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/18.png)

### Git Push to Github

Agora, iremos enviar as mudanças locais até o repositório usando ```git push``` e aprendendo a usar o commit.

![imagem 19](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/19.png)
![imagem 20](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/20.png)


### Git GitHub Branch

Nessa parte, iremos criar uma nova branch através do github:

![imagem 21](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/21.png)


### Git Pull Branch from GitHub

Agora, iremos aprender como atualizar outras branchs no repositório local. Para isso, iremos usar os comandos ```git pull``` para atualizar ```git branch``` para listar as branchs e ```git checkout _branch name_``` para mudar de branch.

![imagem 22](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/22.png)
![imagem 23](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/23.png)
![imagem 24](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/24.png)
![imagem 25](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/25.png)
![imagem 26](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/26.png)
![imagem 27](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/27.png)

### Git Push Branch to GitHub

Nessa seção, iremos criar uma branch nova:

![imagem 28](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/28.png)

Subir algumas alterações:

![imagem 29](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/29.png)

E então fazer o pull request, levando as alterações da branch update-readme para a branch-test

![imagem 30](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/30.png)
![imagem 31](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/31.png)
![imagem 32](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/32.png)
![imagem 33](https://github.com/RafaelTechio/relatorio-tecnico-github/blob/master/imagens/33.png)

## Resultados

Como resultado após a realização dos tutoriais, pude reforçar os comandos básicos e a lógica de git: como criar um repositório, gerenciar seus arquivos, criar commits, gerenciar branchs e mergea-las.

## Conclusão

O uso do github é benéfico para o dia a dia da área de programação pois permite uma série de funcionalidades como versionamento, histórico, co-programing e mais.
