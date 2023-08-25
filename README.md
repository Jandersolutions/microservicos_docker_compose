# Microserviços com Docker Compose: Django, PostgreSQL e Redis
## Este repositório contém um exemplo de configuração para executar microserviços usando Docker Compose, com um serviço Django, um serviço PostgreSQL e um serviço Redis.

## Pré-requisitos
Certifique-se de ter o Docker e o Docker Compose instalados em sua máquina antes de começar.

## Configuração
###### Clone este repositório para o seu ambiente local:
```git clone https://github.com/seu-usuario/seu-repositorio.git```
```cd my_microservices_project```
###### Configure o Django:
###### Coloque o seu código Django no diretório django_app/your_django_code/.
###### Personalize o arquivo django_app/requirements.txt com as dependências da sua aplicação Django.
###### Configure o PostgreSQL:
###### Ajuste os arquivos de configuração PostgreSQL em postgres_config/ conforme necessário.
###### Configure o Redis:
###### Personalize o arquivo de configuração Redis em redis_config/redis.conf conforme necessário.
## Executando os Microserviços
###### Dentro do diretório do projeto, execute o seguinte comando para iniciar os microserviços:
```docker-compose up```
###### Acesse sua aplicação Django no navegador em ```http://localhost:8000```
###### Encerrando os Microserviços
###### Para interromper os microserviços, pressione Ctrl + C no terminal onde você executou o comando docker-compose up. Em seguida, você pode executar o seguinte comando para remover os contêineres:
```docker-compose down```
