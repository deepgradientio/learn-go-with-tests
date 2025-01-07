

.PHONY: all fmt vet test build

all: fmt vet test build

fmt:
	go fmt ./...

vet: fmt
	go vet ./...

test:
	go test ./... -v

build:
	go build -o bin/hello .