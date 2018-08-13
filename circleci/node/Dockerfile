FROM circleci/node:8.11.1

MAINTAINER William Weiss <william@codification.org>

RUN apt-get -y -qq update \
    && apt-get -y -qq install python3.4-dev \

RUN curl -O https://bootstrap.pypa.io/get-pip.py \
    && python3.4 get-pip.py --user \
    && install awscli --upgrade --user \
    && aws --version