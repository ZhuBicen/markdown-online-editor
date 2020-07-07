FROM ubuntu:20.04
COPY sources.list /etc/apt/sources.list
ARG DEBIAN_FRONTEND=noninteractive
ENV TZ=Asia/Shanghai
RUN apt-get update && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN apt-get install nodejs tzdata -y
RUN npm install -g yarn
