FROM arugaldocker/arthas

ADD /1.0/docker-entrypoint /usr/bin/docker-entrypoint
RUN chmod +x /usr/bin/docker-entrypoint
RUN echo "Asia/Shanghai" > /etc/timezone

RUN apk --update add fontconfig ttf-dejavu

ENTRYPOINT [ "/usr/bin/tini", "--", "/usr/bin/docker-entrypoint"]