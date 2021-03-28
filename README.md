# go_hello_docker
Building a Golang Docker image


Run the code:
```go
go build -o hello
```

run the program
```shell
./hello
```

build docker image
```shell
docker image build -t hello .
```

list images
```shell
docker images
```

run your container image
```shell
docker container run -p 8888:8888 hello
```

testing
```shell
curl localhost:8888
```