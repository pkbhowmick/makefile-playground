hey: one two
	@echo $@
	@echo $?
	@echo $^

one::
	touch one

two::
	touch two


clean:
	rm -rf hey one two

one::
	@echo "Testing double colon rule"

two::
	@echo "Testing double colon rule"

