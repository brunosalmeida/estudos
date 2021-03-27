# RabbitMQ

## Overview
- Protocolos
    - AMQP
    - MQTT
- Consumer/Puplisher

## Exchanges
- Faz o router
    - Exchanges
    - Filas
- Tipos de exchange
    - Direct
        - Fila default 
        - By pass para qualquer fila com o mesmo nome de routingKey
    - Fanout
        - Broadcast da msg para todas a filas
    - Topics
        - Utiliza routingKey para match da fila.
            - o match pode ser parcial com o nome da routingKey
    - Headers
        - Utiliza os header para match da fila.
            - Any
            - All
- Pode ser durável
    - Sobrevive ao restart do broker
- Pode ser Auto Delete
    - Destruída quando não tem filas

- Pra que serve cada tipo?

- O que são routingKeys

## Filas
- Tipos
    - Nomeadas
    - Anônimas
        - Duvidas-Cenários úteis?
            - cenário 1
            - cenário 2 
- Duráveis
    - Sobrevive ao restart do broker
- Não durável
- Exclusivas
    - Só permitem 1 consumer
    - Destruída se não há consumers
- Filas não exclusivas
- Auto Delete
    - DSestrói quando não há consumers



