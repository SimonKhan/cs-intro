Python functions

Think of functions as a block of code that you can execute wherever you place them. Functions are portable and you can insert them whenver you want to re-use a certain part of your code. Functions can take input parameters, and return an output.



For example, a function that prints out a statement whenever you call it.

Code (1a)

    # defining the function
    def print_hello():
    	print("this is a function being called printing hello")
     
    
    # calling/using the function
    print_hello()
    print_hello()
    print_hello()
    
    # as you can see, I can call it as much times as I want. The output of this function is the following

Output (1a)

    this is a function being called printing hello
    this is a function being called printing hello
    this is a function being called printing hello
    [Finished in 0.1s]



Functions can also take an input, and return an output

Code (1b)

    # defining the function with two parameters, x and y.
    def add_two_numbers(x, y):
        sum = x + y
        print(sum)
        return sum
     
    # calling/using the function
    add_two_numbers(5, 2)
    add_two_numbers(10, 3)
    add_two_numbers(0, 8)
    
    # as you can see, I can call it as much times as I want and re-use the adding logic with different parameters. The output of this code is the following.
    
    # since this function returned something (the sum of two numbers), I can use the output in my code.
    
    output = add_two_numbers(20, 4)
    print("The sum of 20 and 4 is ", output)

Code (1b)

    7
    13
    8
    24
    ('The sum of 20 and 4 is ', 24)
    [Finished in 0.1s]


