# WebAssembly with Go
Golang v1.20.2

## Compile to wasm
Go to folder "/webassembly/cmd/wasm/"
Run command: GOOS=js GOARCH=wasm go build -o  ../../assets/json.wasm

## Run webserver
Go to folder "webassembly/cmd/server/"
Run command: go run main.go

## Test WASM program
Open Web Browser to URL http://localhost:9090/
Open Javascript Console (Web browser)
And try: formatJSON('{"website":"golangbot.com", "tutorials": {"string":"https://golangbot.com/strings/"}}')
