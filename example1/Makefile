.PHONY : all create clean

all: create  edit

create: 
	@echo "Creating a simple test file"
	touch test.txt

clean:
	@echo "Cleaning up"
	rm *.txt

edit: test.txt
	@echo "Editing test.txt"
	echo "abcdef" > test.txt

