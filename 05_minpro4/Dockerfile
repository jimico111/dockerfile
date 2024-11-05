FROM golang:1.16

RUN go get -d github.com/hashicorp/learn-go-webapp-demo
WORKDIR cd pkg/mod/github.com/hashicorp/learn-go-webapp-demo*

EXPOSE 8080


CMD go run webapp.go
