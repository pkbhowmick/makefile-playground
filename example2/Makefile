BIN :=

REGISTRY ?=

VERSION ?=

SRC_DIRS :=

ALL_PLATFOMS := linux/amd84

OS := $(if $(GOOS), $(GOOS), $(shell go env GOOS))
ARCH := $(if $(GOARCH),$(GOARCH),$(shell go env GOARCH))

BASEIMAGE ?=

TAG := $(VERSION)_$(OS)_$(ARCH)

BUILD_IMAGE ?= go-rest-api: 
