# Modelo esquemático do Retificador de onda

<img src="./modelo_esquematico.jpeg" alt="Modelo Esquemático"> 

## 🛠️ Componentes Utilizados

- TR1: Transformador (reduz a tensão CA)

- BR1: Ponte retificadora (converte CA em CC pulsante)

- C1 (1µF): Capacitor de filtragem para suavizar a tensão CC

- C2 (22nF) e C3 (22nF): Capacitores de desacoplamento para estabilidade do regulador

- U1 (7805): Regulador de tensão (fornece 5V DC estáveis)

- R1 (220Ω): Resistor limitador de corrente para o LED

- D1 (LED-RED): LED indicador de saída regulada

## ⚡ Funcionamento

Transformação da tensão:O transformador TR1 reduz a tensão CA da rede elétrica para um nível adequado.

Retificação:A ponte de diodos BR1 converte a CA em CC pulsante.

Filtragem:O capacitor C1 ajuda a suavizar as oscilações da tensão retificada.

Regulação:O 7805 estabiliza a tensão em 5V DC.

Indicação:O LED D1 acende para indicar que a saída regulada está funcionando.