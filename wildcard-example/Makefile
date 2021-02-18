ALL_PLATFORMS := linux/amd64 linux/arm linux/arm64 windows/amd64

GO_VERSION := 1.15.6
OS := windows

BIN_EXTENSION :=

ifeq (${OS},windows)
  BIN_EXTENSION := .exe
endif

PLATFORMS = $(foreach PLATFORM,$(ALL_PLATFORMS),$(subst /,_,$(PLATFORM)))

#if-else shorter version
version := $(if $(GO_VERSION),$(GO_VERSION),Go Version not found)

some_file := $(wildcard *.txt)

print-%:
	@echo $*
	@echo ${BIN_EXTENSION}
	@echo ${PLATFORMS}

show-file:
	@echo ${SOME_FILE}

show-version:
	@echo ${version}

build-%-image:
	@echo $*


