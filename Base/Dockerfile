FROM selenium/base:3.1.0-astatine
MAINTAINER Selenium <yangle@zs5s.com>

RUN sed -i 's/archive.ubuntu.com/mirrors.aliyun.com/'       /etc/apt/sources.list
RUN apt-get update -qqy \
  && apt-get -qqy --no-install-recommends install \
    fonts-noto-cjk 

