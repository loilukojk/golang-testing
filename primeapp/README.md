# PrimeApp

## Checking Test Coverage (Overview)
```bash
go test -cover
```

## Checking test coverage (detail)
```bash
go test -coverprofile=coverage && go tool cover -html=coverage
```

## To run test command (no verbose)
``` bash
    go test
```

## To run test command (with verbose)
``` bash
    go test -v
```