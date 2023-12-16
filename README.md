# projeto_docker

## criar imagem 
docker build -t nomeUsuarioDocker/projeto_docker:1.0.0 .

## Executar projeto
docker container -d -p 8080:80 --name=nomeContainer nomeUsuarioDocker/nomeImagem:TAG
