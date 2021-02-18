# string substitution syntax: $(subst from,to,text)
bar := ${subst not, totally, "I am not superman"}
foo := a b c

# $(strip string) Remove leading and trailing whitespace in string
clean_str := $(strip a b c  )   #returns 'a b c'

# foreach function
str := $(foreach wrd,$(foo),$(wrd)!)
var :=

# if function
chk := $(if $(var),var has value,var is empty)  #check first argument is non empty,
                                             # then run second else run third argument

# call function
new_func = Variable Name: $(0) First: $(1) Second: $(2) Empty Variable: $(3)


# $(firstword names...)
first_word := $(firstword foo bar)   # return foo

# $(lastword names...)
last_word := $(lastword foo bar)    #return bar



all:
	@echo $(bar)
	@echo $(str)
	@echo $(chk)
	@echo $(call new_func, go, tigers, go)
	@echo $(shell ls -la)			#shell function
	@echo $(clean_str)
	@echo $(first_word)
	@echo $(last_word)





