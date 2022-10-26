# Comandos

- docker run hello-world

verifica primeiro se a imagem existe, baixa ela caso não exista no seu pc
e depois da o start.
a flag '-it' abre o terminal da imagem

- docker start 

inicializa o conteiner

- docker rm 'id'

remove o container selecionado

- docker container prune

remove todos os container inativos

- docker rmi 'id'

remove a imagem selecionada

- docker port 'id'

verifica qual porta o container está utilizando

- docker run -v 'caminho\Local:/caminho_Container'

cria um container e salva os dados no Docker Host

## Docker Compose

- criar um nginx

- criando um docker-compose.yml(ver arquivo docker-compose.yml)

- instalando docker-compose:
    - sudo curl -L https://github.com/docker/compose/releases/download/1.15.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
    - sudo chmod +x /usr/local/bin/docker-compose




