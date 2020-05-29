#
# Dockerfile for mosquitto
#

FROM alpine
MAINTAINER kev <noreply@easypi.pro>

RUN apk add --no-cache ca-certificates mosquitto

VOLUME /etc/mosquitto
EXPOSE 8883

ENTRYPOINT ["mosquitto"]
CMD ["-c", "/etc/mosquitto/mosquitto.conf"]
