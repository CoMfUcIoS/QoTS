clean: clean-go clean-build

clean-build:
	rm -f qots

clean-go:
	go clean -testcache -r

build:
	go build -o qots .

test-go:
	go test -v ./...

fmt-go:
	go fmt ./...

lint-go:
	golangci-lint run --new-from-rev=main