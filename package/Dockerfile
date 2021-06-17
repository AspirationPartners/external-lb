FROM alpine:3.13
RUN apk add --no-cache ca-certificates 
COPY external-lb /usr/bin/
ENTRYPOINT ["/usr/bin/external-lb"]
