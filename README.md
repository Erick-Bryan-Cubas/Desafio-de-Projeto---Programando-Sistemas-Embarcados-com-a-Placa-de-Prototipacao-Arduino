# Controle de Temperatura com Arduino Uno

Este projeto implementa um sistema de controle de temperatura utilizando um Arduino Uno, um sensor LM35, LEDs e um relé. O código foi desenvolvido em C++ para a plataforma Arduino e simulado no [Tinkercad](https://www.tinkercad.com).

## Descrição do Código

O código realiza as seguintes tarefas:

1. Define variáveis e constantes para representar os pinos de entrada e saída, bem como valores de estado e temperatura.
2. Inicializa os pinos como entrada ou saída e inicia a comunicação serial na função `setup()`.
3. Lê o estado do botão e alterna o modo de funcionamento entre "Stop" e "Start" na função `loop()`.
4. Quando o modo "Start" está ativado, o código lê o valor do sensor LM35, calcula a tensão e a temperatura, e ativa ou desativa o relé e os LEDs de acordo com a temperatura medida.
5. Quando o modo "Stop" está ativado, todos os LEDs são ligados e o relé é desligado.

## Componentes

| Nome          | Quantidade | Componente         |
|---------------|------------|--------------------|
| U1            | 1          | Arduino Uno R3     |
| Rpot1         | 1          | 250 kΩ Potenciômetro |
| P1            | 1          | 0.4 , 5  Fonte de energia |
| Meter1        | 1          | Tensão Multímetro  |
| M1            | 1          | Motor CC           |
| T1            | 1          | Transistor NPN (BJT) |
| R1, R2, R3, R4, R5 | 5     | 1 kΩ Resistor      |
| D1            | 1          | Vermelho LED       |
| D2            | 1          | Amarelo LED        |
| D3            | 1          | Verde LED          |
| S1            | 1          | Botão              |

## Simulação no Tinkercad

O projeto foi simulado no Tinkercad, uma plataforma online para simulação e prototipagem de circuitos eletrônicos. Você pode acessar o projeto no Tinkercad através do seguinte link:

[Controle de Temperatura com Arduino Uno - Tinkercad](https://www.tinkercad.com/things/iYxnBnez4qb?sharecode=12FWx8srtYdriS6_XnnDntfiJoq0AmqEVjo1moKcw9M)
