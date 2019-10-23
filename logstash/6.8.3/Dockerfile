FROM docker.elastic.co/logstash/logstash:6.8.3
MAINTAINER joe.gao <kuqq2005@qq.com>
USER 0
RUN set -eux; \
        ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime; \
        echo "Asia/Shanghai" > /etc/timezone;
ENV LANG "en_US.utf8"
