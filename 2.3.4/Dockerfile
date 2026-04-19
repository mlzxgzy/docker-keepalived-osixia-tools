FROM osixia/keepalived:2.3.4
RUN apk add --no-cache redis mysql-client curl && \
    rm -rf /var/cache/apk/* && \
    rm -rf /root/.cache && \
    rm -rf /tmp/*
