FROM golang:latest

ADD . /go/src/github.com/EwanValentine/project/api

RUN go get github.com/go-martini/martini

RUN go install github.com/EwanValentine/project/api

ENTRYPOINT /go/bin/api

EXPOSE 3000
