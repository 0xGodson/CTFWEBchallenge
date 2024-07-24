FROM golang:1.23rc2
COPY app /app
WORKDIR /app
RUN go build
CMD ["/app/updater"]