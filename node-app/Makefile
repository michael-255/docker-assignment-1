NAME = my-node-app

build:
	docker build -t $(NAME):latest .

run:
	docker run --rm -d -p 3000:3000 --name $(NAME) $(NAME):latest

stop:
	docker stop $(NAME)

clean:
	docker rmi $(NAME)

info:
	docker image ls
	docker ps

.PHONY: build run stop clean info
