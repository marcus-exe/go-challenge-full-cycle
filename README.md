## Hello World in GO inside a Docker file

1. Initialize the Module 
```
go mod init containerized-go-app
```
2. Create a main file
```
touch main.go
```
3. Create a Dockerfile and run the following commands:
```
docker build . -t go-containerized:latest
docker run go-containerized:latest
```
# go-challenge-full-cycle
