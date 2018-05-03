FROM jupyter/base-notebook:7fd175ec22c7

USER root

RUN apt-get update -qqy && apt-get install -qqy autoconf dh-autoreconf gcc git libssl-dev pkg-config

USER jovyan

RUN yes | pip install cytoolz==0.9.0 rlp==0.6.0 ecdsa matplotlib pillow qrcode savoir ethereum web3

WORKDIR /home/jovyan
