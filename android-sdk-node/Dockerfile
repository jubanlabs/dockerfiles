FROM runmymind/docker-android-sdk:latest
RUN apt-get update && apt-get install gnupg2 -y
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN apt install nodejs -y
RUN rm -rf /var/cache/apt/*
