# FDS golang webapi
this small project should be a prototype for the FDS webservice written in golang

## Setup
Make sure you have go 1.16 installed with

```bash
go version
```

For livereload the too air is used, so make sure to install this on your development machine and also make sure the GOPATH is added to your PATH variable

```bash
# binary will be $(go env GOPATH)/bin/air
curl -sSfL https://raw.githubusercontent.com/cosmtrek/air/master/install.sh | sh -s -- -b $(go env GOPATH)/bin
```

## Start the development server
Starting the dev server in development mode is simple just type the following command into your terminal

```bash
make dev
```