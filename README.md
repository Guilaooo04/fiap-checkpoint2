# README.md

Este repositório contém a aplicação Fiap Checkpoint 01.

### Pré-requisitos
* Java 17+
* Docker
* Acesso à internet
* Acesso ao Docker Hub

### Instruções de Uso

Antes de executar a aplicação, é necessário obter a imagem do Docker Hub. Utilize o seguinte comando:

```bash
docker pull tome04/fiap-checkpoint2

Isso irá baixar a imagem necessária para executar a aplicação em seu ambiente local.

Para executar com o perfil "dev", utilize o seguinte comando:

```bash
Copy code
docker run -d -p 8080:8080 -e PROFILE=dev tome04/fiap-checkpoint2

Após a execução da aplicação, você poderá acessá-la em http://localhost:8080/h2-console. Esta rota estará disponível apenas quando a aplicação estiver sendo executada a partir do perfil "dev".
