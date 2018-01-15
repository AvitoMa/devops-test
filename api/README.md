### Description
This project is a Golang API accepting in the query string a number as parameter, and calculate the factorial of this number by sending a request to the Factorial TCP server.

### How to run Localy
`go run server.go`

### How to build
`go build server.go`
You can use environment variables to specify the destination binary arch `GOOS` and `GOARCH`

#### Example building in different ARCH:
MacOS : `GOOS=darwin GOARCH=amd64 go build server.go`
Linux 64 : `GOOS=linux GOARCH=amd64 go build server.go`

### Usage
`./server`

### Dependencies
* Golang 1.7+
* TCP Factorial server

### TODO
* Register the API IP:port in a service discovery once UP