FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y\
  vim neovim nano \
  git git-lfs \
  zip unzip \
  curl make build-essential xz-utils file tree \
  sudo \
  libssl-dev pkg-config \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /main

