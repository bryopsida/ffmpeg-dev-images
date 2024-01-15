FROM node:lts
USER 0
RUN apt-get -y update && apt-get -y install ffmpeg v4l-utils ocl-icd-libopencl1 opencl-headers clinfo && rm -rf /var/lib/apt/lists/*
USER node
