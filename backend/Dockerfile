FROM golang:1.13-alpine3.10

RUN mkdir -p /go/src/app
WORKDIR /go/src/app

ADD . /go/src/app

RUN go get -v
