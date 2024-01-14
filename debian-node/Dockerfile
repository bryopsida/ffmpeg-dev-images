FROM node:lts
USER 0
RUN apt-get -y update && apt-get -y install ffmpeg && rm -rf /var/lib/apt/lists/*
USER node
