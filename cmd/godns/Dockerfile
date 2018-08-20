FROM frolvlad/alpine-glibc:latest
RUN apk add --update --no- cache ca-certificates
COPY godns /
RUN chmod +x /godns
ENTRYPOINT ["./godns", "-c", "/usr/local/godns/config.json"]
