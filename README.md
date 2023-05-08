# Estudando-Arduino
Iniciar uma serie de experiências com arduino. 
Alguns dias parados montei meu arduino, o melhor, eu ganhei este arduino.
Fiz alguns teste, ligando o arduino no computador, efetuando a instalação da aplicação, seguindo as instruções do site https://docs.arduino.cc/software/ide-v1/tutorials/Windows consegui efetuar a instalação.
Esta foi a parte facil.
Para o meu primeiro projeto(Queria mesmo era saber se estava tudo funcionando) escolhi o mais simples

ligar um LED


![image](https://user-images.githubusercontent.com/95048518/236868879-2fd404e8-d792-49f1-a93d-57ebc6054104.png)




Peguei com a galera do Tecdicas este tutorial simples, e testei


void setup() 
{

  // Colocamos o pino 12 do Arduino como OUTPUT (saída)
  pinMode(12, OUTPUT);
  
}

// Este código é chamado automáticamente pelo Arduino, ficará em loop até que seu Arduino seja desligado


void loop() 
{

  // Ativamos o pino 12 (colocando 5v nele)  
  digitalWrite(12, HIGH);

  // Aguardamos 1 segundo
  delay(1000);

  // Desligamos o pino 12
  digitalWrite(12, LOW);

  // Aguardamos mais um segundo
  delay(1000);

  // Este código irá se repetir eternamente
}
