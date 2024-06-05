FROM ubuntu:20.04
ARG DEBIAN_FRONTEND=noninteractive
ENV TZ=Asia/Jerusalem
ENV XDG_RUNTIME_DIR=/tmp
RUN apt update
RUN apt upgrade -y
RUN apt install -y git cmake build-essential gdb
RUN apt install -y qtbase5-dev libqt5svg5-dev libqt5websockets5-dev \
    libqt5opengl5-dev libqt5x11extras5-dev libprotoc-dev libzmq3-dev \
    liblz4-dev libzstd-dev
# FROM base
# WORKDIR /src
# RUN git clone --recurse-submodules https://github.com/adamkatav/PlotJuggler.git && \
#     mkdir PlotJuggler/build && \
#     cd PlotJuggler/build && \
#     cmake -DCMAKE_BUILD_TYPE=Debug .. && \
#     make -j && \
#     make install
