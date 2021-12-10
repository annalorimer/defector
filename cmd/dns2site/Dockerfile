FROM golang:latest

RUN apt-get update && apt-get -y install vim sudo 
#COPY ./
RUN go get github.com/pylls/defector/cmd/dns2site
WORKDIR /go/pkg/mod/github.com/pylls/defector@v0.0.0-20160928162217-73a59cb67ebb/cmd/dns2site
RUN go mod init dns2site
RUN go get github.com/deckarep/golang-set
