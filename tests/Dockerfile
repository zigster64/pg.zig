from postgres:latest

RUN localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
ENV LANG en_US.utf8

env POSTGRES_USER root
env POSTGRES_PASSWORD root_pw
