FROM alpine:3.8

LABEL maintainer="lezhi2018@gmail.com"

ENV TERM="xterm" \
	LANG="C.UTF-8" \
	LC_ALL="C.UTF-8"

RUN set -x \
	&& apk add --no-cache bash ca-certificates \
	&& ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime