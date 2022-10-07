FROM golang:1
COPY app /app
WORKDIR /app
RUN go build
CMD ["/app/updater"]