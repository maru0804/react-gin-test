FROM golang:1.16

COPY go.mod /api/go.mod
COPY go.sum /api/go.sum
WORKDIR /api
RUN ls
RUN go mod download

COPY . /api

CMD go run main.go