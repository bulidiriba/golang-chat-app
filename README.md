# golang-chat-app



1. Run the server

        go run main.go
        

2. Run two client in different terminal so that they communicate each other

        cd client

        go run main.go

        go run main.go



### To run With docker

1. To build

        sudo docker build --tag=golang_chat_app .

2. To run the server

        docker run -it -p 8080:8080 golang_chat_app

3. Run two different client in different terminal, so that they communicate with each other

        cd client

        go run main.go -N tensor

        go run main.go -N Foo




