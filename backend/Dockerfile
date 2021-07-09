FROM golang

ENV GO111MODULE=on

RUN mkdir /app
WORKDIR /app

COPY go.mod .
COPY go.sum .

RUN go mod download

COPY . .

RUN CGO_ENABLED=0 GOOS=linux go build cmd/main.go

EXPOSE 8088

ENTRYPOINT ["/app/main"]
