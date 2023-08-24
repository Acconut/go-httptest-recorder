# go-httptest-recorder

This package is copy of Go's `net/http/httptest.ResponseRecorder` with support for recording 1XX responses, which is currently not supported in the standard library.

It is based on the great work from [Kévin Dunglas](https://github.com/dunglas), who [proposed](https://github.com/golang/go/issues/56346) and [implemented](https://github.com/golang/go/pull/56151) the new API. As of writing this, the proposal has not been accepted yet, which is why this package exists. It can be used until we have native support for this in the standard library. Thank you very much, Kévin!

## Installation

```
go get github.com/Acconut/go-httptest-recorder
```

## Documentation

https://pkg.go.dev/github.com/Acconut/go-httptest-recorder
