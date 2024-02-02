FROM golang:1.22rc2-bookworm
COPY app /app
WORKDIR /app
RUN go build
CMD ["/app/updater"]