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