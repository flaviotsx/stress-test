# Stress test

A tool for doing stress testing using golang

## Configuration instructions

```bash
go mod tidy
```

## Usage

The application use three essential parameters:
- `--url` or `-u`: the target URL for performing stress tests
- `--requests` or `-r`: the total number of requests to execute
- `--concurrency` or `-c`: the number of simultaneous requests to run

### Running

```bash
go run main.go --url "https://www.google.com" --requests 1000 --concurrency 100
```
#### Or
```bash
docker run container_name --url "http://www.google.com" --requests 100 --concurrency 10
```