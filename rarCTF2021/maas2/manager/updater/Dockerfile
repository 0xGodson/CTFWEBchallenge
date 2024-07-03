FROM golang:1.22.5
COPY app /app
WORKDIR /app
RUN go build
CMD ["/app/updater"]