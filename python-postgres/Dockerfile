FROM alpine:latest

ARG ENV_NAME
WORKDIR /home
RUN apk add python3 \
    py3-pip \
    curl \
    git \
&& python3 -m pip install --upgrade pip \
&& python3 -m venv ${ENV_NAME}

