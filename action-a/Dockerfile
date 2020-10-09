FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN ls
RUN ls /
RUN cat /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["entrypoint.sh"]
