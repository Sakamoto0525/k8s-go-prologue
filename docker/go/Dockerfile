FROM golang:1.19-alpine as local

ENV ROOT=/go/src/github.com/Sakamoto0525/k8s-go-prologue

WORKDIR ${ROOT}
COPY . .

RUN apk add --no-cache alpine-sdk git && \
    go install github.com/cosmtrek/air@latest
