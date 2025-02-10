# infra-hackathon
Este repositorio tem como objetivo cuidar da infraestrutura de nossas aplicações, e cuidar do processo de CI/CD disponivel no GitHub Actions.

Dentro do projeto é possivel realizar o deploy de 6 aplicações diferentes, sendo elas:
1. Deploy da infraestrutura do EKS;
2. Deploy do postgres para o serviço de usuários;
3. Deploy do postgres para o serviço de envio de mensagens;
4. Deploy para o sonarQube;

Todos estes deploys são realizados utilizando kubernetes.

 ## Segregação de EC2
Para manter um ambiente mais seguro, foi criado uma instancia EC2 para cada banco de dados e outra para as aplicações, ficando assim em 3 nodes.

![Logo da Aplicação](images/infra.jpg)

## Validação de acesso nos Banco de Dados
![Logo da Aplicação](images/database.png)