FROM runmymind/docker-android-sdk:latest
RUN apt-get update && apt-get install gnupg2 zip -y &&  rm -rf /var/cache/apt/*
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash - &&  apt install nodejs -y &&  rm -rf /var/cache/apt/*
RUN npm install -g cordova
RUN curl -s "https://get.sdkman.io" | bash
RUN /bin/bash  -c "source /root/.sdkman/bin/sdkman-init.sh && sdk install gradle"
