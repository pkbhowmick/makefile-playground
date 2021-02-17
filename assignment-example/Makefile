.PHONY: all simple recursive conditional

all: simple recursive conditional

gcc = cc

var1 := ${gcc}
var2 = ${gcc}
var3 ?= conditional

gcc = c++

var3 ?= condional-updated


simple:
	@echo var1=${var1}	#print var1=cc

recursive:
	@echo var2=${var2}	#print var2=c++

conditional:
	@echo var3=${var3}	#print var3=conditional





