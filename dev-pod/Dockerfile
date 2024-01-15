FROM ghcr.io/bryopsida/k8s-dev-pod:main
USER 0
RUN apt-get -y update && apt-get -y install ffmpeg v4l-utils ocl-icd-libopencl1 opencl-headers clinfo && rm -rf /var/lib/apt/lists/*
USER 1001
