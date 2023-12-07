FROM golang:1.20.11

WORKDIR /workspace
COPY . /workspace
RUN go build

ENTRYPOINT ["go", "run", "main.go"]