# projeto-kafka-master-first

## Link para os recursos necessários ao desenvolver o projeto
- [Docker](https://www.docker.com/products/docker-desktop/)
- [VSCode](https://code.visualstudio.com/)
- [Postman](https://www.postman.com/)
- [Intellij](https://www.jetbrains.com/pt-br/idea/download)

# Passos para executar o projeto :
1. Instalar os recursos acima citados;
2. Executar o comando docker no diretório raiz: docker-compose up
3. Executar os módulos na seguinte ordem :
I. lib-commons: Classes comuns a todo projeto, melhorando a evolução, seguindo o conceito SOLId;
II. produces: Responsável pelo envio das mensagens ao kafka, usando spring book;
III. consumers: Responsável por consumir as mensagens que o Kafka recebeu.
4. Enviar as mensagens via Postman, usando a resquest abaixo:
   http://localhost:8080/machines
   body - raw - JSON
  {
   "machineId": 1,
   "machineName": "fernando-tech-001",
   "machineStatus": "ATIVO",
   "machineType": "WORK-SPACE"
   }
5. Acessar o Kafdrop, dashboard/interface para facilitar a visualização dos tópicos e mensagens:
   http://localhost:19000/

### projeto-kafka-master-first: Usa as melhores práticas em desenvolvimento com Java, spring boot e kafka.
