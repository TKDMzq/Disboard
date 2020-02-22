FROM node:13-alpine


# allows proper git credential helper
ARG USERNAME=vscode
ARG USER_UID=1000
ARG USER_GID=$USER_UID 

RUN apk add git openssh;

