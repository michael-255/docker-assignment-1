NAME = my-python-app

build:
	docker build -t $(NAME):latest .

run:
	docker run -it --rm --name $(NAME) $(NAME):latest

stop:
	docker stop $(NAME)

clean:
	docker rmi $(NAME)

info:
	docker image ls
	docker ps

.PHONY: build run stop clean info
