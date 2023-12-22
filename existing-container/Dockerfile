FROM itzg/minecraft-server

WORKDIR /app

COPY whitelist.json /data

COPY build-info.sh /opt

RUN apt-get install jq && /opt/build-info.sh

EXPOSE 25565