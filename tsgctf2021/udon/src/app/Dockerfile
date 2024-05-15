FROM golang:1.21.10

WORKDIR /workspace
COPY . /workspace
RUN go build

ENTRYPOINT ["go", "run", "main.go"]