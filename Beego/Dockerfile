FROM golang:alpine

MAINTAINER howard000@gmail.com

RUN apk add --no-cache git make


# install beego
RUN go get -u github.com/astaxie/beego

# install bee
RUN go get github.com/beego/bee

EXPOSE 8080


CMD ["bee", "run"]


