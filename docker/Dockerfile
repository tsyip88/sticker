FROM resin/rpi-raspbian:stretch
RUN apt-get update
RUN apt-get install -y \
  sass \
  golang \
  git \
  libraspberrypi-bin \
  python3 \
  python3-dev \
  python3-pip \
  python3-picamera \
  libatlas-base-dev \
  libopenjp2-7-dev \
  libjpeg-dev \
  libfreetype6-dev \
  libtiff5-dev \
  protobuf-compiler

RUN pip3 install --no-cache-dir --default-timeout=1000 tensorflow
RUN pip3 install pillow
RUN pip3 install matplotlib

