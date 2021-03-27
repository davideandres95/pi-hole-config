FROM balenalib/raspberry-pi-alpine:latest
RUN apk --update-cache add dhcp-helper
EXPOSE 67 67/udp
ENTRYPOINT ["dhcp-helper", "-n"]
