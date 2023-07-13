# Componentes Básicos
## A placa
Conhecendo um pouco a placa do Arduino Uno:

Obs: Há vários tipos de Arduino! Existem o Arduino Uno, Arduino Leonardo, Arduino Mega, Arduino Micro...

![image](https://github.com/maripnv/InicianteArduino/assets/82036846/1064de25-a78d-4bcf-bc8c-5206400212e8)

---
## O ambiente de desenvolvimento (IDE)
A Arduino IDE é um software de código aberto (open source), operado em funções C e C++. 
A IDE pode ser instalada gratuitamente clicando [aqui](https://www.arduino.cc/en/software), caso apareça alguma mensagem que se refere a doação, saiba que não é preciso doar para baixá-la. A IDE é bem intuitiva e didática. Para ir salvando seu código, lembre-se sempre do "ctrl + s" e se apagou tudo sem querer e quer voltar, nosso salvador "ctrl + z" lhe ajuda!! :smiley:
![image](https://github.com/maripnv/InicianteArduino/assets/82036846/108b63a0-71fd-4bcb-b06a-6118690245ff)

---
## Componentes usados nos projetos
Todos os componentes listados são adquiridos no kit da Robocore, e eles vendem separadamente no próprio site! E todos os textos abaixo, de modo resumido, foram extraídos do curso que a [Robocore](https://www.robocore.net/) fornece após adquirir o kit, porém há maior detalhamento no curso.

- Resistor: Limita a corrente elétrica que passa pelo circuito, seu valor pode variar. É medido em Ohm (Ω) seguindo essa [tabela](https://github.com/maripnv/InicianteArduino/assets/82036846/cdf7796e-c5dc-447d-8894-bc2a6ce7dbf3).
  
- LED: Emite uma luz quando uma corrente o excita (apenas em uma direção, do pino mais longo para o pino mais curto). O pino/chanfro/terminal menor é o negativo (catodo) enquanto o maior é o positivo (anodo). Clica [aqui](https://github.com/maripnv/InicianteArduino/assets/82036846/7f3209c4-c468-49f1-9e6c-615a0d48ef80)
 para ver um led. [Fonte da imagem](https://www.oficinabrasil.com.br/noticia/tecnicas/multimetros-automotivos-analise-e-resolucao-de-problemas-complexos-parte-final).

- [Chave Momentânea](https://github.com/maripnv/InicianteArduino/assets/82036846/f52abdc1-1a13-4b9c-bb5a-c67bf99f7550): Quando o botão é apertado, os contatos entre os terminais de cada lado são ligados entre si. A foto extraída foi retirada do site da Robocore.
  
- [Buzzer](https://github.com/maripnv/InicianteArduino/assets/82036846/f897a771-4a8c-4df1-a3a0-51c3185584de): Quando uma corrente elétrica passa por ele, ele emite um som.

- [Diodo Laser](https://github.com/maripnv/InicianteArduino/assets/82036846/1fca3daa-8a53-40c3-a131-1b1d67651c5f): Emite um laser quando uma corrente o excita (apenas em uma direção, do cabo vermelho para o azul).
  
- [Sensor de Luminosidade LDR](https://github.com/maripnv/InicianteArduino/assets/82036846/7c301316-e58a-4867-8549-db10eb93928a): É uma resistência que varia conforme a luminosidade que incide sobre ele muda.
  
- [Potenciômetro](https://github.com/maripnv/InicianteArduino/assets/82036846/ba176e9c-bf3b-4df1-8569-55d8f151603d): Varia a resistência entre os terminais conforme a haste superior é girada.
  
- [Sensor de Temperatura e Umidade DHT11](https://github.com/maripnv/InicianteArduino/assets/82036846/5afa27f5-7995-4c91-ad43-b22b3561204c): Um sensor digital com um único fio de sinal, capaz de ler temperatura e umidade.
  
- [LED RGB](https://github.com/maripnv/InicianteArduino/assets/82036846/c1294a39-1601-41f3-8e94-808cbb692e1d): Pense em três LEDs: um vermelho, um verde e um azul. Agora, junte todos eles em um só. Pronto, isso é um LED RGB.
  
- [Display de 7 Segmentos](https://github.com/maripnv/InicianteArduino/assets/82036846/869d5d8e-766e-4536-849e-06fba271d219): Possui 7 LEDs em formato de número "8", com os quais é possível acender os números de 0 a 9. Ainda possui um LED indicador de ponto.
  
- [Circuito Integrado 4511](https://github.com/maripnv/InicianteArduino/assets/82036846/37742af1-f205-427b-8073-08c7cfb58497): Traduz um número em binário para o display de 7 segmentos, facilitando o uso do display e economizando portas do microcontrolador.
  
- [Sensor Ultrassônico - HC-SR04](https://github.com/maripnv/InicianteArduino/assets/82036846/2ea3e91e-1d02-45d4-b1dd-845fd35199bc): Sensor de distância que usa sinal ultrassônico para identificar a distância até um objeto entre 2 cm e 4 m.
  
- [Módulo Joystick](https://github.com/maripnv/InicianteArduino/assets/82036846/525cd22d-8fac-4ee0-a5c5-96ff261d3b97): Joystick de 3 eixos (X e Y Analógico e Z digital - botão), com funcionamento idêntico aos de controle de videogames.
  
- [Micro Servo 9g SG90](https://github.com/maripnv/InicianteArduino/assets/82036846/bde85a39-d1a5-4190-a19b-8b041721b9bb): Motor de posicionamento ajustável de 0 a 180º através de um pulso de controle.
  
- [Garra Robótica Ant](https://github.com/maripnv/InicianteArduino/assets/82036846/af855855-92be-435f-9e5b-3853a2b63e98): Ela possui uma abertura de 7,4 cm, e consegue segurar pequenos objetos na sua ponta, por exemplo um lápis.
  
- [Protoboard 400](https://github.com/maripnv/InicianteArduino/assets/82036846/fb8155f3-49bf-4ce5-bb10-8b26f9b29fb4): Matriz de contato com 400 pontos que permite conectar componentes eletrônicos sem a necessidade de solda.
  
- [Jumpers](https://github.com/maripnv/InicianteArduino/assets/82036846/28698964-1714-40ed-bcac-ab7c067d5f9e): Cabos com conectores nas extremidades que permitem conectar os componentes entre si por meio da protoboard.
