all: multiply_numbers 

multiply_numbers : multiply_numbers.cpp
	g++ -o multiply_numbers multiply_numbers.cpp

dump: multiply_numbers 
	objdump -d multiply_numbers > multiply_numbers.asm

# Clean target 
clean: 
	rm -f multiply_numbers multiply_numbers.asm

# Run target
run: multiply_numbers
	./multiply_numbers


