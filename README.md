#primeapp

- Checking test coverage (overview)
    go test -cover

- Checking test coverage (detail)
    go test -coverprofile=coverage
    go tool cover -html=coverage

- To run test command (no verbose)
    go test

- To run test command (with verbose)
    go test -v