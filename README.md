# PROJETO 17 - DOCKER TO-DO LIST :computer:

## Esse projeto pertence ao módulo `back-end` da [Trybe](https://www.betrybe.com/) :green_heart:

### Stacks utilizadas no desenvolvimento:
<div style="display: inline_block"><br>
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Shield" />
</div>
 
 #
<details>
 
<summary>
  
## 1- Resumo
  
</summary>

No projeto To Do List foi necessário, com ajuda do Docker, unir as aplicações do Front e Back-End e os testes de integração  que validam se as aplicações estão se comunicando. Deveríamos, em suma, usar comandos específicos do Docker para ajudar na compreensão do código, criar imagens e executar contêineres a partir dessas imagens.

Por fim, a partir da conteinerização das aplicações, criamos conexão entre elas e orquestramos todo o seu funcionamento por meio do Docker compose. Veja mais abaixo!
  
</details>

#

<details>
 
<summary>
 
## 2- Requisitos

</summary>

* I. Crie um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12

* II. Inicie o container 01container

* III. Liste os containers filtrando pelo nome 01container
  
* IV. Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele

* V. Remova o container 01container

* VI. Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container

* VII. Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro

* VIII. Pare o container 02images que está em andamento

* IX. Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend

* X. Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend

* XI. Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests

* XII. Suba uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar

</details>

# 

<details>
 
<summary>

## 3- Nota do Projeto
 
</summary>

## 100% :heavy_check_mark:

![Project-docker-todo-list](https://github.com/jonnoliveira/trybe-project-17-docker-todo-list/blob/main/images/docker-todo-list-grade.png)

</details> 
 
# 
