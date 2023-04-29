# Commander gRPC API for Go

[![Github tag](https://badgen.net/github/tag/flowshot-io/commander-client-go)](https://github.com/flowshot-io/commander-client-go/tags)
[![Go Doc](https://img.shields.io/badge/go-documentation-blue.svg?style=flat-square)](https://pkg.go.dev/github.com/flowshot-io/commander-client-go)
[![Go Report Card](https://goreportcard.com/badge/github.com/flowshot-io/commander-client-go)](https://goreportcard.com/report/github.com/flowshot-io/commander-client-go)
[![GitHub](https://img.shields.io/github/license/flowshot-io/commander-client-go)](https://github.com/flowshot-io/commander-client-go/blob/master/LICENSE)

Generated Go files from Commander [api](https://github.com/flowshot-io/commander-api) repository.

## Usage

To install the package in your project, run the following command:

```bash
go get -u github.com/flowshot-io/commander-client-go
```

## Rebuild

Run `make` once to install all plugins and tools (`protoc` and `go` must be installed manually).

Run `make update-proto` to update submodule and recompile proto files.