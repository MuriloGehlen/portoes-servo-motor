O sistema de controle do portão automático consiste em dois servos (Servo 1 para o lado esquerdo e Servo 2 para o lado direito), quatro botões e seis leds. Os botões têm as seguintes funções: botão 1 abre o lado esquerdo, botão 2 abre o lado direito, botão 3 abre ambos os lados e botão 4 fecha amos os portões. 

Os leds indicam o estado do portão: led 1 (vermelho) indica que o lado esquerdo está fechado, led 2 (verde) indica que o lado esquerdo está aberto, led 3 (vermelho) indica que o lado direito está fechado, led 4 (verde) indica que o lado direito está aberto, led 5 (amarelo) acende quando o portão está em movimento e led 6 (azul) indica que o portão está completamente aberto. 

O sistema acende o led amarelo sempre que o portão está em movimento (abrindo ou fechando), e o led azul acende quando ambos os lados estão abertos. Se ambos os lados estiverem fechados, os leds vermelhos (1 e 3) acendem.
Lista de passos principais:
Definir os pinos dos servos e botões.
definir uma variável para cada botão e cada servo.
Configurar os leds de estado fechado e aberto
colocar uma variável de condição para funcionarem quando o servo estiver em 0 ou 90 graus
Garantir que o led amarelo acenda quando qualquer parte do portão estiver em movimento e o azul quando ambos os lados estiverem abertos (0 graus).

