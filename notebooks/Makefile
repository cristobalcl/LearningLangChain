.PHONY: build run

build:
	docker build -t cristobalcl_img .

run:
	docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$$PWD":/home/jovyan/work cristobalcl_img

