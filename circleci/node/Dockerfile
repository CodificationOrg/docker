FROM circleci/node:8.11.1

MAINTAINER William Weiss <william@codification.org>

RUN sudo apt-get -y -qq update \
    && sudo apt-get -y -qq install python3.4-dev \

RUN curl -O https://bootstrap.pypa.io/get-pip.py \
    && sudo python3.4 get-pip.py \
    && sudo install awscli --upgrade \
    && aws --version