#FROM selenium/base:3.3.1-arsenic
FROM registry.cn-hangzhou.aliyuncs.com/angle/abase:2.1
MAINTAINER Selenium <yangle@zs5s.com>

USER root

RUN apt-get -qqy update \
  && apt-get -qqy --no-install-recommends install \
    fonts-noto-cjk \
  && rm -rf /var/lib/apt/lists/* /var/cache/apt/* \