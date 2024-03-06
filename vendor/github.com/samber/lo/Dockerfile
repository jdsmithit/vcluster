
FROM golang:1.21.8

WORKDIR /go/src/github.com/samber/lo

COPY Makefile go.* ./

RUN make tools
