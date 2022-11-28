FROM golang:1.16

WORKDIR /usr/src/server

COPY . .

RUN go build

RUN go test ./...

ENV PORT=8080

CMD ["./server"]

