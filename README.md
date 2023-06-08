# PythonMegaAssn

ASSIGNMENT 2

Q1. Why do we call Python as a general purpose and high-level programming ?                  language 
=>	The python language is one of the most accessible programming languages available because it has simplified syntax and not 	complicated, which gives more emphasis on natural language. Due to its ease of learning and usage, python codes can be easily 	written and executed much faster than other programming languages.

Q2. Why is Python called a dynamically typed language?
=>	in Python. Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the 	runtime of the program. So, Python is a dynamically typed language. 

Q3. List some pros and cons of Python programming language?
=>  	Pros :- Free and Open source, easy to learn, Vast libraries support, Greater productity, interpreated Language, portability.
	Cons:- Poor Memory efficiency, Slow speed, Database Accesss, Weak on mobile computing, Runtime errers.

Q4. In what all domains can we use Python?
=>    	Python is a high-level and general-purpose programming language. So we can use Python for several purposes, from web development to 	data science, machine learning, and robotics. Python's real-world use cases are limitless.

Q5. What are variable and how can we declare them?
=>    	Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, and 	the value to be assigned to the variable. Unless and until the variables are declared and initialized, they cannot be used in the 	program.


Q6. How can we take an input from the user in Python?
=>	num = input ("Enter number :")
	print(num)
	name1 = input("Enter name : ")
	print(name1)
  
	# Printing type of input value
	print ("type of number", type(num))
	print ("type of name", type(name1))
	
Q7. What is the default datatype of the value that has been taken as an input using input() function?
=>    	By default, input returns a string. So the name and age will be stored as strings.

Q8. What is type casting?
=>	The conversion of one data type into the other data type is known as type casting in python or type conversion in python.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
=>	split( ) function helps us get multiple inputs from the user and assign them to the respective variables in one line. This function 	is generally used to separate a given string into several substrings. However, you can also use it for taking multiple inputs. The 	function generally breaks the given input by the specified separator and in case the separator is not provided then any white space 	is considered as a separator.
	# Python program to take multiple inputs from the user
	a, b = input("Enter two of your lucky number: ").split() 
	print("First lucky number is: ", a) 
	print("Second lucky number is: ", b) 

	Output:
	Enter two of your lucky number: 7 1
	First lucky number is: 7
	Second lucky number is: 1


10. What are keywords?
=>	Keywords are some predefined and reserved words in python that have special meanings. Keywords are used to define the syntax of the 	coding.

Q11. Can we use keywords as a variable? Support your answer with reason.
=>	Keywords are the reserved words in Python. We cannot use a keyword as a variable name, function name or any other identifier.

Q12. What is indentation? What's the use of indentaion in Python?
=>	Indentation in general means indenting words or spaces or lines in the document to follow the styling rule for documentation.                                                                                              	In Python, indentation is one of the most distinctive features, and it can be defined as it refers to the same meaning as that of 	the general, which means that the compiler in Python cannot execute without indentation; therefore, the code is written with some 	spaces or tabs into many different blocks of code to indent it so that the interpreter can easily execute the Python code.

Q13. How can we throw some output in Python?
=>	Using the print() function: The simplest way to throw output in Python is by using the built-in print() function. You can pass one or more arguments to print() to display them as output. Here's an example:

print("Hello, world!")

Q14. What are operators in Python?
=>	+ Addition, - Substraction, * multiplication, / Division, % Modulus, ** Exponentition, // Floor division.

Q15. What is difference between / and // operators?
	'/' is used for the normal division of two numbers.
	'//' is used to obtain the smallest integer nearest to the quotient obtained by dividing two numbers.
	
Q16. Write a code that gives following as an output.
iNeuroniNeuroniNeuroniNeuron

	Print(‘iNeuron’+‘iNeuron’+‘iNeuron’+‘iNeuron’)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
	def isEven(n):
	    return (n % 2 == 0)
     
	# Driver code
	n = 9
	print("Even" if isEven(n) else "Odd")

Q18. What are boolean operator?
	AND, OR, NOT or AND NOT

Q19. What will the output of the following?
1 or 0

0 and 0

True and False and True

1 or 0 or 0

Q20. What are conditional statements in Python?
=>	If statements, if-else statements, elif statements, Nested if and if-else statements,elif ladder

Q21. What is use of 'if', 'elif' and 'else' keywords?
=>	If… elif…else are conditional statements that provide you with the decision making that is required when you want to execute code 	based on a particular condition. The if… elif…else statement used in Python helps automate that decision making process.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
	
	if Age>=18:
	    print("I Can vote")
	else:
	    print("I Can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
numbers = [12, 75, 150, 180, 145, 525, 50]
=> 	
	numbers = [12, 75, 150, 180, 145, 525, 50]
	sum_even = 0

	for num in numbers:
       		 if num % 2 == 0:  # Check if the number is even
        		sum_even += num

	print("Sum of even numbers:", sum_even)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
=>	# Input three numbers
	num1 = float(input("Enter the first number: "))
	num2 = float(input("Enter the second number: "))
	num3 = float(input("Enter the third number: "))

	# Compare the numbers to find the greatest
	if num1 >= num2 and num1 >= num3:
    	greatest = num1
	elif num2 >= num1 and num2 >= num3:
    	greatest = num2
	else:
    	greatest = num3

	# Display the greatest number
	print("The greatest number is:", greatest)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions
	The number must be divisible by five
	If the number is greater than 150, then skip it and move to the next number
	If the number is greater than 500, then stop the loop
numbers = [12, 75, 150, 180, 145, 525, 50]
=>  	for number in numbers:
    if number > 500:
        break
    print(number)

Q26. What is a string? How can we declare string in Python?
=>	Strings can be created by enclosing characters inside a single quote or double-quotes
	Example: "What is a string"

Q27. How can we access the string using its index?
=>	 a string can be accessed by specifying the string name followed by a number in square brackets ( [] ).

Q28. Write a code to get the desired output of the following
string = "Big Data iNeuron"
desired_output = "iNeuron"
=>	string = "Big Data iNeuron"
	desired_output = string.split()[-1]
	print(desired_output)

Q29. Write a code to get the desired output of the following
string = "Big Data iNeuron"
desired_output = "norueNi"
=>	string = "Big Data iNeuron"
	desired_output = string.split()[-1][::-1]
	print(desired_output)

Q30. Resverse the string given in the above question.
=>	string = "Big Data iNeuron"
	reversed_string = string[::-1]
	print(reversed_string)

Q31. How can you delete entire string at once?
=>	We can use string replace() function to replace a character with a new character

Q32. What is escape sequence?
=>	In escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is 	converted into another character or series of characters.

Q33. How can you print the below string?
'iNeuron's Big Data Course'
=>	Print('iNeuron'\s Big Data Course')

Q34. What is a list in Python?
=>	Lists are used to store multiple items in a single variable.

Q35. How can you create a list in Python?
=>	In Python, a list is created by placing elements inside square brackets [] , separated by commas

Q36. How can we access the elements in a list?
=>	List literals are written within square brackets [ ]. Lists work similarly to strings use the len() function and square brackets 	[ ] to access data, with the first element at index 0.

Q37. Write a code to access the word "iNeuron" from the given list.
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
=>	lst = [1, 2, 3, "Hi", [45, 54, "iNeuron"], "Big Data"]
	word = lst[4][2] 
	print(word)

Q38. Take a list as an input from the user and find the length of the list.
=>	# Input a list from the user
	user_list = input("Enter a list of elements, separated by 	spaces: ").split()

	# Calculate the length of the list
	length = len(user_list)

	# Display the length of the list
	print("Length of the list:", length


Q39. Add the word "Big" in the 3rd index of the given list.
lst = ["Welcome", "to", "Data", "course"]
=>	lst = ["Welcome", "to", "Data", "course"]
	lst.insert(3, "Big")  # Inserting "Big" at index 3
	print(lst)


Q40. What is a tuple? How is it different from list?
=>	The primary difference between tuples and lists is that tuples are immutable as opposed to lists which are mutable. Therefore, it is possible to change a list but not a tuple. The contents of a tuple cannot change once they have been created in Python due to the immutability of tuples.


Q41. How can you create a tuple in Python?
=>	A tuple is created by placing all the items (elements) inside parentheses () , separated by commas. 

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
=>	my_tuple = (1, 2, 3)
new_tuple = ("Dinesh",) + my_tuple[1:]  # Creating a new tuple with "John" added

print(new_tuple)


Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
=>	No, two tuples cannot be appended together in Python using the append() method
The append() method is specifically designed for mutable sequences like lists and cannot be used with tuples. It modifies the existing list in-place by adding the specified element as a single item.


Q44. Take a tuple as an input and print the count of elements in it.
=>	my_tuple = tuple(input("Enter elements of the tuple (space-separated): ").split())
	count = len(my_tuple)
	print("Count of elements in the tuple:", count)



Q45. What are sets in Python?
=>	Sets are used to store multiple items in a single variable. Set is one of 4 built-in data types in Python used to store collections of data, the other 3 are List, Tuple, and Dictionary, all with different qualities and usage. A set is a collection which is unordered, unchangeable*, and unindexed.



Q46. How can you create a set?
=>	Using curly braces {}:  my_set = {1, 2, 3, 4}
	Using the set() function:  my_set = set([1, 2, 3, 4])
	Using set comprehension:  my_set = {x for x in [1, 2, 3, 4]}



Q47. Create a set and add "iNeuron" in your set.
=>	my_set = set()
	my_set.add("iNeuron")

	print(my_set)



Q48. Try to add multiple values using add() function.
=>	The add() function in Python's set data type is used to add a single element to the set. It does not accept multiple values as arguments. 




Q49. How is update() different from add()?
=>	We use add() method to add single value to a set. We use update() method to add sequence values to a set. Here Sequences are any iterables including list , tuple , string , dict etc. There is not really any additional values regarding to the already existing answers


Q50. What is clear() in sets?
=>	The method clear is used to clear all the data from the set data structure.



Q51. What is frozen set?
=>	Frozen set is just an immutable version of a Python set object. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation. Due to this, frozen sets can be used as keys in Dictionary or as elements of another set.



Q52. How is frozen set different from set?
=>	Frozenset is similar to set in Python, except that frozensets are immutable, which implies that once generated, elements from the frozenset cannot be added or removed. This function accepts any iterable object as input and transforms it into an immutable object.



Q53. What is union() in sets? Explain via code.
=>	In Python, the union() method is used to find the union of two or more sets. It returns a new set that contains all the unique elements from all the sets being combined.

	set1 = {1, 2, 3}
	set2 = {3, 4, 5}
	set3 = {5, 6, 7}

	union_set = set1.union(set2, set3)

	print(union_set)

Output:
{1, 2, 3, 4, 5, 6, 7}


Q54. What is intersection() in sets? Explain via code.
=>	In Python, the intersection() method is used to find the intersection of two or more sets. It returns a new set that contains only the elements that are common to all the sets being intersected.

	set1 = {1, 2, 3, 4, 5}
	set2 = {4, 5, 6, 7}
	set3 = {3, 4, 5}

	intersection_set = set1.intersection(set2, set3)
	print(intersection_set)

	Output:  {4, 5}



Q55. What is dictionary ibn Python?
=>	In Python, a dictionary is an unordered, mutable, and iterable data structure that stores a collection of key-value pairs



Q56. How is dictionary different from all other data structures.
=>	Dictionaries in Python have some distinct characteristics that differentiate them from other data structures.Here are the key differences between dictionaries and other commonly used data structures:
Mapping of key-value pairs, Unordered, Mutable, Unique keys, Lookup efficiency

Q57. How can we delare a dictionary in Python?
=>	Using curly braces: Define a dictionary by enclosing key-value pairs in curly braces.
	Using the dict() constructor: Create a dictionary using the dict() constructor and provide key-value pairs as arguments or by passing another dictionary or an iterable object.


Q58. What will the output of the following?
var = {}
print(type(var))
=>	<class 'dict'>


Q59. How can we add an element in a dictionary?
=>	Using assignment operator (=): Assign a value to a new key or an existing key to add or update the element.
	Using the update() method: The update() method allows you to add multiple key-value pairs from another dictionary or an iterable object.

	
Q60. Create a dictionary and access all the values in that dictionary.
=>	my_dict = {
    'Car': 'BMW',
    'Truck': 'Ashok Leyland'
	}

	# Accessing all values in the dictionary
	for value in my_dict.values():
	    print(value)

Q61. Create a nested dictionary and access all the element in the inner dictionary.
=>	# Creating a nested dictionary
nested_dict = {
    'outer_key1': {
        'inner_key1': 'value1',
        'inner_key2': 'value2',
        'inner_key3': 'value3'
    },
    'outer_key2': {
        'inner_key4': 'value4',
        'inner_key5': 'value5',
        'inner_key6': 'value6'
    },
    'outer_key3': {
        'inner_key7': 'value7',
        'inner_key8': 'value8',
        'inner_key9': 'value9'
    }
}

# Accessing elements in the inner dictionary
for outer_key, inner_dict in nested_dict.items():
    for inner_key, value in inner_dict.items():
        print(f'Outer Key: {outer_key}, Inner Key: {inner_key}, Value: {value}')

Q62. What is the use of get() function?
=>	Get() method is used in Python to retrieve a value from a dictionary. dict. get() returns None by default if the key you specify 	cannot be found. With this method, you can specify a second parameter that will return a custom default value if a key is not found.

Q63. What is the use of items() function?
=>	In Python Dictionary, items() method is used to return the list with all dictionary keys with values. Parameters: This method takes 	no parameters. Returns: A view object that displays a list of a given dictionary's (key, value) tuple pair.

Q64. What is the use of pop() function?
=>	Python list pop() is an inbuilt function in Python that removes and returns the last value from the List or the given index value.

Q65. What is the use of popitems() function?
=>	Python dictionary popitem() method removes the last inserted key-value pair from the dictionary and returns it as a tuple.

Q66. What is the use of keys() function?
=>	The keys() method in Python Dictionary, returns a view object that displays a list of all the keys in the dictionary in order of 	insertion using Python.

Q67. What is the use of values() function?
=>	It is used to collect all the values from a dictionary. It does not take any parameter and returns a dictionary of values.

Q68. What are loops in Python?
=>	for loop, while loop, and nested loop.

Q69. How many type of loop are there in Python?
=>	for loop, while loop, and nested loop.

Q70. What is the difference between for and while loops?
=>	The for loop is used when we know the number of iterations, that is, how many times a statement must be executed. That is why, when 	we initialize the for loop, we must define the ending point. A while loop is used when the number of iterations is unknown.

Q71. What is the use of continue statement?
	The continue statement in Python returns the control to the beginning of the while loop. The continue statement rejects all the 	remaining statements in the current iteration of the loop and moves the control back to the top of the loop. The continue statement 	can be used in both while and for loops.

Q72. What is the use of break statement?
	It is used to control the sequence of the loop. Suppose you want to terminate a loop and skip to the next code after the loop; break 	will help you do that. A typical scenario of using the Break in Python is when an external condition triggers the loop's 	termination.
	
Q73. What is the use of pass statement?
	The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid 	getting an error when empty code is not allowed. Empty code is not allowed in loops, function definitions, class definitions, or in 	if statements.

Q74. What is the use of range() function?
	The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a 	specified number.

Q75. How can you loop over a dictionary?
	You can loop through a dictionary by using a for loop. When looping through a dictionary, the return value are the keys of the dictionary, but there are methods to return the values as well.

Coding problems
Q76. 	Write a Python program to find the factorial of a given number.
=>
	def factorial(n):
    	  if n == 0 or n == 1:
        	return 1
    	  else:
        	return n * factorial(n-1)

	# Get user input
	number = int(input("Enter a number: "))

	# Calculate factorial
	result = factorial(number)

	# Print the result
	print("The factorial of", number, "is", result)


Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
=>
	# Get user input
	principal = float(input("Enter the principal amount: "))
	rate = float(input("Enter the rate of interest: "))
	time = float(input("Enter the time period in years: "))

	# Calculate simple interest
	simple_interest = (principal * rate * time) / 100

	# Print the result
	print("The simple interest is:", simple_interest)


Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
=>
	# Get user input
	principal = float(input("Enter the principal amount: "))
	rate = float(input("Enter the rate of interest: "))
	time = float(input("Enter the time period in years: "))

	# Calculate compound interest
	amount = principal * (1 + rate / 100) ** time
	compound_interest = amount - principal

	# Print the result
	print("The compound interest is:", compound_interest)


Q79. Write a Python program to check if a number is prime or not.
=>
	def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n**0.5) + 1):
        if n % i == 0:
            return False
    return True

	# Get user input
	number = int(input("Enter a number: "))

	# Check if the number is prime
	if is_prime(number):
   	 print(number, "is a prime number.")
	else:
   	 print(number, "is not a prime number.")


Q80. Write a Python program to check Armstrong Number.
=>
	def is_armstrong(number):
    	  digits = list(str(number))
      	  num_digits = len(digits)
    	  armstrong_sum = sum(int(digit) ** num_digits for digit in digits)
    	  return armstrong_sum == number

	# Get user input
	number = int(input("Enter a number: "))

	# Check if the number is an Armstrong number
	if is_armstrong(number):
    		print(number, "is an Armstrong number.")
	else:
    		print(number, "is not an Armstrong number.")

Q81. Write a Python program to find the n-th Fibonacci Number.
=>
	def fibonacci(n):
    if n <= 0:
        return "Invalid input! Please enter a positive integer."
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        a, b = 0, 1
        for _ in range(n - 2):
            a, b = b, a + b
        return b

# Get user input
n = int(input("Enter the value of n: "))

# Find the n-th Fibonacci number
fib_number = fibonacci(n)

# Print the result
print("The", n, "th Fibonacci number is:", fib_number)


Q82. Write a Python program to interchange the first and last element in a list.
=>
	def interchange_first_last(lst):
    if len(lst) >= 2:
        lst[0], lst[-1] = lst[-1], lst[0]
    return lst

# Get user input
elements = input("Enter elements of the list separated by spaces: ").split()

# Convert elements to a list
lst = list(elements)

# Interchange the first and last element
result = interchange_first_last(lst)

# Print the result
print("The list with the first and last elements interchanged:", result)


Q83. Write a Python program to swap two elements in a list.
=>
	def swap_elements(lst, index1, index2):
    if index1 < len(lst) and index2 < len(lst):
        lst[index1], lst[index2] = lst[index2], lst[index1]
    return lst

# Get user input
elements = input("Enter elements of the list separated by spaces: ").split()

# Convert elements to a list
lst = list(elements)

# Get the indices of elements to swap
index1 = int(input("Enter the index of the first element to swap: "))
index2 = int(input("Enter the index of the second element to swap: "))

# Swap the elements
result = swap_elements(lst, index1, index2)

# Print the result
print("The list with the elements swapped:", result)


Q84. Write a Python program to find N largest element from a list.
=>
	def find_n_largest_elements(lst, n):
    sorted_lst = sorted(lst, reverse=True)
    return sorted_lst[:n]

# Get user input
elements = input("Enter elements of the list separated by spaces: ").split()
n = int(input("Enter the value of N: "))

# Convert elements to a list
lst = list(map(int, elements))

# Find the N largest elements
largest_elements = find_n_largest_elements(lst, n)

# Print the result
print("The", n, "largest elements in the list:", largest_elements)


Q85. Write a Python program to find cumulative sum of a list.
=>
	def cumulative_sum(lst):
    cum_sum = []
    total = 0
    for num in lst:
        total += num
        cum_sum.append(total)
    return cum_sum

# Get user input
elements = input("Enter elements of the list separated by spaces: ").split()

# Convert elements to a list
lst = list(map(int, elements))

# Find the cumulative sum
cumulative_sum = cumulative_sum(lst)

# Print the result
print("The cumulative sum of the list:", cumulative_sum)


Q86. Write a Python program to check if a string is palindrome or not.
=>
	def is_palindrome(string):
    reversed_string = string[::-1]
    return string == reversed_string

# Get user input
string = input("Enter a string: ")

# Check if the string is a palindrome
if is_palindrome(string):
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")

	
Q87. Write a Python program to remove i'th element from a string.
=>
	def remove_element(string, index):
    if index < len(string):
        new_string = string[:index] + string[index+1:]
        return new_string
    return string

# Get user input
string = input("Enter a string: ")
index = int(input("Enter the index of the element to remove: "))

# Remove the i'th element from the string
result = remove_element(string, index)

# Print the result
print("The string after removing the element:", result)


Q88. Write a Python program to check if a substring is present in a given string.
=>
	def is_substring_present(string, substring):
    return substring in string

# Get user input
string = input("Enter a string: ")
substring = input("Enter a substring: ")

# Check if the substring is present in the string
if is_substring_present(string, substring):
    print("The substring is present in the string.")
else:
    print("The substring is not present in the string.")


Q89. Write a Python program to find words which are greater than given length k.
=>
	def find_words_greater_than_length(string, k):
    words = string.split()
    result = [word for word in words if len(word) > k]
    return result

# Get user input
string = input("Enter a string: ")
k = int(input("Enter the value of k: "))

# Find words greater than length k
result = find_words_greater_than_length(string, k)

# Print the result
print("Words greater than length", k, "in the string:", result)


Q90. Write a Python program to extract unquire dictionary values.
=>
	# Input dictionary
	input_dict = {'a': 1, 'b': 2, 'c': 3, 'd': 2, 'e': 1}

	# Extract unique values
	unique_values = list(set(input_dict.values()))

	# Print the unique values
	print(unique_values)


Q91. Write a Python program to merge two dictionary.
=>
	# Two dictionaries to merge
	dict1 = {'a': 1, 'b': 2}
	dict2 = {'c': 3, 'd': 4}

	# Merge dictionaries using the update() method
	merged_dict = dict1.copy()
	merged_dict.update(dict2)

	# Print the merged dictionary
	print(merged_dict)


Q92. Write a Python program to convert a list of tuples into dictionary.
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
=>
	# Input list of tuples
	input_list = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]

	# Convert list of tuples to dictionary
	result = {key: value for key, value in input_list}

	# Print the result
	print(result)


Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
=>
	# Input list
	input_list = [9, 5, 6]

	# Create list of tuples with number and its cube
	result = [(num, num ** 3) for num in input_list]

	# Print the result
	print(result)


Q94. Write a Python program to get all combinations of 2 tuples.
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
=>	
	from itertools import product

	# Input tuples
	test_tuple1 = (7, 2)
	test_tuple2 = (7, 8)

	# Generate all combinations
	combinations = list(product(test_tuple1, test_tuple2))

	# Print the combinations
	print(combinations)


Q95. Write a Python program to sort a list of tuples by second item.
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
=>	
	# Input list of tuples
	data = [('for', 24), ('Geeks', 8), ('Geeks', 30)]

	# Sort the list by the second item
	sorted_data = sorted(data, key=lambda x: x[1])

	# Print the sorted list
	print(sorted_data)


Q96. Write a python program to print below pattern.
* 
* * 
* * * 
* * * * 
* * * * * 
=>	num_rows = 5
	for i in range(num_rows):
	    for j in range(i + 1):
	        print("* ", end="")
	    print()


Q97. Write a python program to print below pattern.
    *
   **
  ***
 ****
*****
=>	num_rows = 5
	for i in range(num_rows):
	    for j in range(num_rows - i - 1):
	        print(" ", end="")
	    for k in range(i + 1):
	        print("*", end="")
	    print()


Q98. Write a python program to print below pattern.
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
=>	num_rows = 5
	for i in range(num_rows):
	    for j in range(num_rows - i - 1):
	        print(" ", end="")
	    for k in range(i + 1):
	        print("* ", end="")
	    print()


Q99. Write a python program to print below pattern.
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
=>	num_rows = 5
	for i in range(num_rows):
    	  for j in range(i + 1):
            print(j + 1, end=" ")
    	print()


Q100. Write a python program to print below pattern.
A 
B B 
C C C 
D D D D 
E E E E E 

=>	num_rows = 5
	for i in range(num_rows):
    	   for j in range(i + 1):
        	print(chr(65 + i), end=" ")
    	print()


