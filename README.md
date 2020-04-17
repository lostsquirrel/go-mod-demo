# go-mod-demo
go-mod demo

## command

- `go mod init` creates a new module, initializing the go.mod file that describes it.
- `go build`, `go test`, and other package-building commands add new dependencies to go.mod as needed.
- `go list -m all` prints the current module’s dependencies.
- `go get` changes the required version of a dependency (or adds a new dependency).
- `go mod tidy` removes unused dependencies.

## ref

https://blog.golang.org/using-go-modules