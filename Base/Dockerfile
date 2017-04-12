FROM selenium/base:3.3.1-arsenic
MAINTAINER Selenium <yangle@zs5s.com>

RUN sed -i 's/archive.ubuntu.com/mirrors.aliyun.com/'       /etc/apt/sources.list
RUN apt-get update -qqy \
  && apt-get -qqy --no-install-recommends install \
    fonts-noto-cjk 