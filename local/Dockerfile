FROM ubuntu:latest

RUN apt-get update && apt-get install -y squid

COPY . /etc/squid

CMD squid -f /etc/squid/squid.conf -NYCd 1
