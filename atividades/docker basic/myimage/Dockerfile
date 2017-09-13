FROM ubuntu:16.04
FROM nginx
RUN apt-get update
RUN apt-get install -y iputils-ping vim
ENTRYPOINT ["ping", "-c", "3"]
EXPOSE 80 8080
CMD ["127.0.0.1"]


