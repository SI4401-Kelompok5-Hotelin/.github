# Hotelin-WAD

Hotelin is an app for user searching hotel in user area. This project built with javascript framework named [React](https://reactjs.org/docs/getting-started.html) and CSS framework named [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/) and [Chakra UI](https://chakra-ui.com). This project is a part of Web Application Development course in [Telkom University](https://telkomuniversity.ac.id).

## Developer behind this project
- [Abdi Fatih](https://github.com/fatihabdi)
- [Aulia Ulfa Cheni](https://github.com/auliaucheni)
- [Fauzan Nur Fachri Afiansyah](https://github.com/fauzanafiansyah)
- [Muhammad Kautsar Firdaus](https://github.com/kautsarfrds)
- [Sabrina Hidayah](https://github.com/sabrinah11)

## Repository Structure

The repository is structured as follows:

- `main` is main branch of the repository and contains the latest stable version of the code.
- `dev` is the development branch of the repository and contains the latest development version of the code.
- `feature/feature_name` branches are used to develop new features and are merged into `dev` when they are ready.
- commits formatted as `feat/feature_name` are used to fix bugs in the code and are merged into `dev` when they are ready.

## Installation

## Front End 

### Prerequisites

- ReactJS 18.2.0
- NodeJS LTS

### Running the application

```bash
npm i && npm start
```

## Back End
## Prerequisites

- [Go](https://golang.org/dl/)
- [Docker](https://docs.docker.com/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Running the application

- Install dependencies

```bash
$ go mod download
```

- Run the application

```bash
$ docker-compose up
$ go run main.go
```

Running the application will create a database named `hotelin` in your local PostgreSQL instance.