PROJECT_NAME=topic-controller

docker_build: java_build
all: docker_build docker_push
clean: java_clean

include ../Makefile.docker

include ../Makefile.maven

.PHONY: build clean release
