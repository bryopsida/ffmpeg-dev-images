FROM ghcr.io/bryopsida/k8s-dev-pod:main
USER 0
RUN apt-get -y update && apt-get -y install ffmpeg && rm -rf /var/lib/apt/lists/*
USER 1001
