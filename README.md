# Go Web Programming

This is the code repository for the Go Web Programming book

## Prerequisites

- Buy the [book](https://www.manning.com/books/go-web-programming)
- Install [go](https://golang.org/) `brew install go`
- Install [dep](https://github.com/golang/dep) `brew install dep`

## Setup
- set your [gopath](https://golang.org/doc/code.html#GOPATH) (e.g. `export GOPATH=$HOME/code/go`)
- clone this git repo into $GOPATH/github.com/sausheong/gwp `git clone https://github.com/sausheong/gwp $GOPATH/github.com/sausheong/gwp`
- cd $GOPATH/github.com/sausheong/gwp
- run `dep ensure`
- run `go build ./...`
- run `go test ./...`
- run `go install ./...`

Or run this one liner:

``` bash
dep ensure && go build ./... && go test ./... && go install ./...
```

If you see the tests in Chapter 2 failing you just need to setup the Postgres database.

You can [install Postgres here](https://www.postgresql.org/download/).

Once Postgres is installed follow the instructions in the book to setup the sql database for the chapter that requires it.

Happy Coding!