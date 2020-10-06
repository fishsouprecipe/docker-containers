FROM debian:stable-slim

MAINTAINER Ivan Komissarov <fishsouprecipe@gmail.com>

RUN apt-get update
RUN apt-get install -y wget
RUN wget --no-check-certificate https://www.python.org/ftp/python/3.9.0/Python-3.9.0a2.tar.xz

CMD ["echo", "Hello World..."]
