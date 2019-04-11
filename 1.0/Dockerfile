FROM arugaldocker/arthas

ADD docker-entrypoint /usr/bin/docker-entrypoint
RUN chmod +x /usr/bin/docker-entrypoint

ENTRYPOINT [ "/usr/bin/tini", "--", "/usr/bin/docker-entrypoint"]