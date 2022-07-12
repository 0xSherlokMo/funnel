FROM golang:1.17.11-alpine3.16

RUN apk add --no-cache git \
    binutils-gold \
    curl \
    g++ \
    gcc \
    gnupg \
    libgcc \
    linux-headers \
    make

RUN go mod tidy

CMD go run main.go