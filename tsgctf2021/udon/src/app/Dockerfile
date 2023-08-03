FROM golang:1.19.11

WORKDIR /workspace
COPY . /workspace
RUN go build

ENTRYPOINT ["go", "run", "main.go"]