From rabbitmq:latest

MAINTAINER chenbo "1126531273@qq.com"

WORKDIR /usr/local

RUN rabbitmqctl add_user chenbo chenbo && rabbitmqctl set_user_tags chenbo Admin

EXPOSE 5672
EXPOSE 15672

CMD ["rabbitmq-server"]


