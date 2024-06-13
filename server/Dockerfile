FROM golang:1.19

WORKDIR /app

COPY *.go ./

RUN GOOS=linux go build -o /hello main.go

EXPOSE 8080

CMD ["/hello"]

