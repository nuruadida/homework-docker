FROM golang:1.16-alpine

WORKDIR /app

COPY . .

RUN go build -o todo

EXPOSE 8080

CMD ./todo
