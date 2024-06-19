-----

# Relatório do Projeto: Semáforo Inteligente

Link do projeto: https://www.tinkercad.com/things/1wYMIABaMs2-semaforo-inteligente

-----

# Introdução

- Este projeto simula um semáforo inteligente utilizando a plataforma Tinkercad. São mostrados dois sinais, um para carros e outro para pedestres simulando um estrada. Ao pressionar o botão, o sinal de de carros fecha e o de pedestres abre, permitido que atravessem em segurança. Enquanto o sinal de carros ficar fechado, um contador é inciado mostrando quanto tempo falta para abrir novamente, com o incremento de um alerta sonoro.

-----

# Planejamento

Objetivos:

- Criar um semáforo funcional para carros e pedestres.
- Implementar um display de sete segmentos para contagem regressiva.
- Adicionar um buzzer para emitir sons específicos quando o sinal de pedestres abre e fecha.
  
Componentes Necessários:

- 1 x Arduino UNO
- 5 x LEDs (vermelho, amarelo e verde)
- 1 x Buzzer
- 1 x Display de sete segmentos
- Resistores
- Fios de conexão
- Protoboard

-----

# Montagem

Passos de Montagem:

Configuração do Semáforo:

- LEDs para os carros (vermelho, amarelo, verde) e para os pedestres (vermelho, verde).

Display de Sete Segmentos:

- Pinos do display de sete segmentos (A-G) aos pinos digitais do Arduino.

Buzzer:

- Buzzer ao pino A1 do Arduino (positivo no pino A1 e negativo no GND).

Esquema de Conexões:

- led1 (vermelho carros): pino 2
- led2 (amarelo carros): pino 3
- led3 (verde carros): pino 4
- led4 (vermelho pedestres): pino 6
- led5 (verde pedestres): pino 7

Display de Sete Segmentos:

- segA: pino 8
- segB: pino 9
- segC: pino 10
- segD: pino 11
- segE: pino 12
- segF: pino 13
- segG: pino A0

- buzzer: pino A1

-----

# Resultados Obtidos

Funcionamento do Semáforo:

- O semáforo para carros alterna entre verde, amarelo e vermelho corretamente.
- O semáforo para pedestres alterna entre vermelho e verde corretamente.

Display de Sete Segmentos:

- O display de sete segmentos conta de 8 a 0 durante o sinal vermelho para carros, proporcionando uma contagem regressiva.

Buzzer:

- O buzzer emite um som de 1000 Hz por 500 ms quando o sinal de pedestres abre.
- O buzzer emite um som de 400 Hz por 250 ms quando o sinal de pedestres fecha.

-----









