FROM ubuntu:latest

CMD ["echo", "Hello World"]

WORKDIR /app 
RUN apt-get update && apt-get install vim -y

COPY ./html /usr/share/nginx/html