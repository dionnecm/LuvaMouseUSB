# LuvaMouseUSB
Projeto de hardware para sensor de retirada de equipamentos

Este projeto tem por objetivo possibilitar o uso do ponteiro do mouse em um computador com sistema operacional Windows por uma pessoa que não tenha o movimento fino suficiente para utilizar um mouse ou touchpad.
Uma placa Arduino Nano é a central de processamento que adquire os dados de inclinaço e movimentação do acelerômetro do módulo MPU 6050 e envia para um computador através da porta serial USB.
Um programa escrito em Java captura os dados da porta serial e efetua o controle do ponteiro do mouse. A inclinação das mãos efetua o controle do ponteiro do mouse através dos seguintes movimentos: 
a) Inclinação para a frente: move o ponteiro do mouse para baixo; 
b) Inclinação para trás: move o ponteiro do mouse para cima; 
c) Inclinação para a esquerda: move o ponteiro do mouse para a esquerda; 
d) Inclinação para a direita: move o ponteiro do mouse para a direita; 
e) Movimento para baixo: click do mouse.
