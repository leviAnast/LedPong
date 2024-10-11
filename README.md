# Kernel de Processos com Jogo de LEDs e Botões

Este projeto implementa um kernel de processos simples para um jogo interativo usando LEDs e botões em uma plataforma Arduino. Os jogadores controlam a direção de uma "bola de luz" representada por LEDs, e competem para ver quem chega ao final primeiro.

## Funcionalidades

- **Kernel de Processos**: 
  - Gerencia a adição, execução e organização dos processos.
  - Implementa uma fila circular para armazenar e acessar processos com base em seus deadlines.
  
- **Jogo de LEDs**: 
  - Um LED simula a "bola" que se move entre os LEDs.
  - Dois botões permitem que os jogadores alterem a direção da "bola".
  - Quando a "bola" atinge uma extremidade, o jogador oposto vence.

- **Efeitos Visuais e Sonoros**:
  - Um buzzer emite um som ao final do jogo.
  - LEDs piscam para indicar o vencedor.

## Componentes Necessários

- **Hardware**:
  - 1 Arduino (ou outra placa compatível)
  - 9 LEDs
  - 2 Botões
  - 1 Buzzer
  - Resistores para LEDs e botões, se necessário
  
## Pinagem do Arduino

- **LEDs**: Pinos digitais 5 a 13.
- **Botões**: Pinos digitais 3 e 4.
- **Buzzer**: Pino digital 16 (ou outro pino digital disponível).


