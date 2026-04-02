FROM debian:latest
LABEL org.opencontainers.image.authors="Jhon Doe <jhon_doe@gmail.com>" \
      org.opencontainers.image.version="1.0.0" \
      org.opencontainers.image.description="A simple Debian-based image for my application" \
      org.opencontainers.image.source="github.com" \
      org.opencontainers.image.url="myurl.com"
RUN apt update && apt install -y linuxlogo
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
