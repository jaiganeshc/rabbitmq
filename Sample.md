
docker run --rm --pid=host -d -h rabbitmq-ouc -p 5672:5672 -p 15672:15672 -v [/var/lib/rabbitmq/mnesia]:/var/lib/rabbitmq/mnesia --name rabbitmq rabbitmq:latest /usr/sbin/rabbitmq-server
