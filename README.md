# To-do list

<p align="right">
  <img src="./gopher.png" alt="Gopher">
</p>

This project is a Go-based REST API that allows users to manage to-do lists through a simple and intuitive interface. It features a robust backend with an SQLite database and includes functionalities for dealing with to-do lists. The project also includes a comprehensive set of integration tests and a Makefile for easy building and testing. The project is designed with clean, maintainable code and follows best practices for structuring Go applications.

Developed with Go 1.22, utilising the updated ["net/http"](https://go.dev/blog/routing-enhancements) package routing enhancements.

**The project is still in progress and should be finished soon.**

## To-dos

- [x] utilise "net/http" package routing enhancements
- [x] GORM
- [x] Set up for Test Driven Development
- [x] Lists
  - [x] [Integration Tests](https://github.com/thefactus/todo-list/blob/main/tests/lists_handlers_test.go)
- [ ] Tasks
  - [ ] Integration Tests
- [ ] Authentication
  - [ ] Integration Tests
- [ ] Databases support
  - [x] SQLite
  - [ ] PostgreSQL
- [x] Add go-playground/validator
- [ ] Create a Logger package
- [ ] Add Swagger
- [ ] Add Go Docs

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## MakeFile

run all make commands with clean tests

```bash
make all build
```

build the application

```bash
make build
```

run the application

```bash
make run
```

Create DB container

```bash
make docker-run
```

Shutdown DB container

```bash
make docker-down
```

live reload the application

```bash
make watch
```

run the test suite

```bash
make test
```

clean up binary from the last build

```bash
make clean
```
