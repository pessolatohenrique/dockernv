# Docker Env

### Sobre

O objetivo deste projeto é centralizar as configurações de containers via Docker, facilitando as prévias configurações necessárias para os projetos

### Tecnologias abstraídas

- Sonarqube
- Toolkit Node: Redis, MySQL, MongoDB, Kafka, Zookeeper

### Instalação do projeto

Acesse o diretório da tecnologia desejada (exemplo: sonarqube):

    cd sonarqube

Realize o mapeamento de volumes no arquivo docker-compose do diretório desejado:

    volumes:
        - /yourlocalpath:/opt/sonarqube/data

Execute o projeto:

    docker-compose up -d --build
