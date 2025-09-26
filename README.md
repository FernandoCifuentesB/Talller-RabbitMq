# Taller Rabbit Mq

Para iniciar con nuestro taller, tenemos que crear nuestro docker-compose, nuestro sender.py (envía mensajes a una queue) y nuestro receiver.py (recibe mensajes de la queue)
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/82714cd2-6e3d-4826-9ce1-7821177a1cc4.jpg)

Al tener nuesto docker-compose listo, hacemos el levantamiento de RabbitMQ:

![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/edit/main/README.md)

Y accedemos a nuestro panel de rabbit para confirmar que funcione:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/edit/main/README.md)

Procedemos a ejecutar nuestro receiver.py:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/edit/main/README.md)

Al ver que funciona, en otra consola ejecutamos el sender.py:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/blob/main/1a701f39-b386-416e-9c6a-c8b830ffda71.jpg)
y veremos como en nuestra consola de receiver.py nos llega nuestro mensaje:
![Texto alternativo](https://github.com/FernandoCifuentesB/Talller-RabbitMq/edit/main/README.md)

De esta forma completamos el primer punto de nuestro taller de RabbitMQ :D
