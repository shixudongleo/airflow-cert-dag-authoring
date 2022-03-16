# Astronomer Cloud CLI

The Astronomer Cloud CLI can be used to build Airflow DAGs locally and run them via docker-compose, as well as to deploy those DAGs to Astronomer-managed Airflow clusters and interact with the Astronomer API in general.

## Local Development

1. Install `go` 1.7+ - https://go.dev/doc/install
2. Install `golangci-lint` to run linter locally

    ```brew install golangci-lint```

    ```golangci-lint run .```
3. Install `pre-commit` to run lint on every commit
    
    ```brew install pre-commit```

    ```pre-commit install```
    
    Run lint locally:

    ```pre-commit run --all-files```

