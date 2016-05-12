# RabbitMQ Work & Tutorials

The code here is based on all the tutorials found in the RabbitMQ website.

**Make sure the RabbitMQ server is already running!**

All the code listed here are compilable in my machine. If you have any issues in compiling/running them, create an issue in the github repository and let me know.

Reading this small code base assumes you have some experiences in queues such as activemq or jms, and that you know queue principles such as producer/consumer model, publish/subscribe model, etc

Since I am using my own directory structure, compiling and running the code must ensure the classpath correctly points to the relevant jar libraries.
- e.g. in src, *javac -cp .:../lib/rabbitmq-client.jar hk/ust/cse/fchenaa/named/queue/Send.java hk/ust/cse/fchenaa/named/queue/Recv.java -d ../bin/hk/ust/cse/fchenaa*
- e.g. in bin, *java -cp .:../lib/rabbitmq-client.jar hk.ust.cse.fchenaa.named.queue.Send*

Note that you might not be able to directly run the program through Eclipse. It crashes when I attempt to run it directly inside Eclipse. Some Eclipse errors were thrown.

This is the first version. In the subsequent versions, I will structure the directory and include comments to the source code. Reading my succint comments will be easier than reading the tutorials :)

