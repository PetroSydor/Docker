Docker build:

docker build rabbitmq:3.6.11 -t rabbitmq:3.6.11


Docker run example program:

docker run  --name rabbitmq -d -p 4369:4369 -p 5672:5672 -p 15672:15672 -p 25672:25672 rabbitmq:3.6.11

P.S. TLS ready, but not implemented in this build
