# NOTES

## stunnel tests

docker run -d -p 8020:80 nginx

apk add --update --no-cache \
 ca-certificates \
 gettext \
 libintl \
 openssl \
 stunnel

/etc/stunnel/stunnel.key:ro \

/etc/stunnel/stunnel.pem:ro \

    dweomer/stunnel

docker run -it -p 8025:625 \
 -v /Users/saminda/git/docker_tests/keys/:/etc/stunnel/ \
 alpine:latest \
 /bin/sh
