# Taller Rabbit Mq

Para iniciar con nuestro taller, tenemos que crear nuestro docker-compose, nuestro sender.py (envía mensajes a una queue) y nuestro receiver.py (recibe mensajes de la queue)
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/82714cd2-6e3d-4826-9ce1-7821177a1cc4.jpg)

Al tener nuesto docker-compose listo, hacemos el levantamiento de RabbitMQ:

![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/65ddefc0-20aa-4bbc-a5f6-1ef0721461b1.jpg)

Y accedemos a nuestro panel de rabbit para confirmar que funcione:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/155b76ab-f515-4c66-a2af-8fcf5163a18e.jpg)

Procedemos a ejecutar nuestro receiver.py:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/63c4fdc3-3e52-4a0a-b147-6634ec524e70.jpg)

Al ver que funciona, en otra consola ejecutamos el sender.py:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/1a701f39-b386-416e-9c6a-c8b830ffda71.jpg)

y veremos como en nuestra consola de receiver.py nos llega nuestro mensaje:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/21eafd0a-804a-43f4-8333-61d124eddd2f.jpg)

De esta forma completamos el primer punto de nuestro taller de RabbitMQ :D



