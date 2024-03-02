FROM rabbitmq:3.12.0-management
RUN apt-get update && apt-get install -y wget
RUN rabbitmq-plugins enable rabbitmq_management
EXPOSE 5672 15672
CMD ["rabbitmq-server"]