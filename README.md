# consumidor-estoque

Este projeto é o consumidor das mensagens da api microsservico-estoque-preco.
As mensagens são gerênciadas pelo rabbitmq e este consumer é desenvolvido na linguaguem java na forma de um microsservico.

## Arquitetura

Produtor: Um microserviço desenvolvido em Java com Spring Boot que publica mensagens em uma fila do RabbitMQ.

Consumidor Java: Microserviço desenvolvido em Java com Spring Boot que consome mensagens da fila.

Consumidor Node.js: Um segundo microserviço, desenvolvido em Node.js, também responsável por consumir mensagens da mesma fila.

## Diagrama de arquitetura

![diagramaRabbitmq](https://github.com/user-attachments/assets/0ea28ae0-e961-45d2-bac3-059eadffc22d)
