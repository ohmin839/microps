FROM ubuntu:24.04

ARG USERNAME=ubuntu

RUN apt-get update && \
    apt-get install -y \
        build-essential \
        git \
        iproute2 \
        iputils-ping \
        netcat-openbsd \
        sudo && \
    echo "$USERNAME ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER $USERNAME
