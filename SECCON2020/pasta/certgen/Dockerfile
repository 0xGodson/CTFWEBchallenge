FROM alpine:3.18.3

# Install OpenSSL
RUN apk update && \
    apk add --no-cache openssl && \
    rm -rf "/var/cache/apk/*"


ADD ./certgen.sh /
WORKDIR /certs
ENTRYPOINT ["sh", "/certgen.sh"]