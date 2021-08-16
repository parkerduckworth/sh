## Quickstart

	# start an http server
	python3 -m http.server

	# build
	GOOS=js GOARCH=wasm go build -o parser.wasm

	# point your browser at the http server
	firefox http://localhost:8000/

If main.go changes, rebuild via the Go command and refresh the page.

Tested on Go 1.16.7. Will need changes to work on Go 1.17.