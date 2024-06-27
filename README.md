[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15311164&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
    Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding

    Key Features:
    1. Readability and Simplicity - ython's syntax is clean and easy to understand, the use of indentation to define code blocks enhances readabilit 

    2. Interpreted Language - Python code is executed line by line, which makes debugging easier and faster

    3. Dynamically Typed - Variables in Python do not need explicit declarations, meaning types are determined at runtime.

    4. Extensive Standard Library - Python has a comprehensive standard library that supports many common programming tasks such as file I/O, system calls, and internet protocols

    5. Cross-Platform - Python is available on various platforms, including Windows, macOS, and Linux, making it highly portable.

    Use Cases:
     1. Web Development - Frameworks like Django and Flask make it easy to build robust and scalable web applications. 

     2. Data Science and Machine Learning - Libraries like NumPy, pandas, and TensorFlow make Python a preferred choice for data analysis, scientific computing, and machine learning.

     3. Automation and Scripting - Python's simplicity and powerful libraries make it an ideal choice for writing scripts to automate repetitive tasks.

     4. Game Development - Libraries such as Pygame are used for creating simple games and multimedia applications.

     5. Embedded Systems- Microcontrollers like the Raspberry Pi can run Python, allowing for the development of embedded systems and IoT projects.




2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
    1. Download python installer form the web 
       - Download form the official site https://www.python.org/downloads/

    2. Run the installer 
       - Run the installer once it is downloaded and check the add to path both
       - Click install

    3. Verify installations
       - Open command prompt
       - Tye the command 'python --version'
       - It should display the version of the python you installed

    4. Set up a virtual environment
       - Open terminal
       - Navigate to your project directory using
       - Create a virtual environment by running python3 -m venv env
       
3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
      print("Hello, World!")

         - Print - This is a finction that outputs text
         - Hello world - This is a string, which is a sequence of characters enclosed in quotation marks.
         - Parantheses () - The parentheses are used to enclose the arguments of the print function
         - Quatation marks "" -  The double quotation marks enclose the string that you want to print.
    

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
      1. Integer (int) - Whole numbers without a decimal point

      2. Float (float) - Numbers with a decimal point

      3. String (str) -  sequence of characters enclosed in single or double quotes.

      4. Boolean (bool) - Represents True or False

      5. List (list) - An ordered, mutable collection of items, enclosed in square brackets.


      age = 21
      print(age)

      height = 5.7
      print(height)

      name = "James"
      print(name)

      is_student = True
      print(is_student)

      cars = ["nissan", "ford", "toyota", "mazda"]
      print(cars)

      ![alt text](<Data typrs.png>)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
    - Conditional statements in Python allow one to execute certain pieces of code based on whether a condition is true or false
   e.g if-else statement
         age = 18

         if age >= 18:
            print("You can vote")
         else:
            print("You are too young to vote")

      - The if statement checks if the condition age >= 18 is true.
      - If the condition is true, the code block under the if statement is executed and prints "You can vote"
      - If the condition is false, the code block under the else statement is executed printing "You are too young to vote"

    LOOPS:
     - Loops allow you to execute a block of code multiple times. Python supports two main types of loops for loops and while loops.
       Example of for loop
        cars = ["nissan", "ford", "toyota", "mazda"]

        for car in cars:
            print(car)


      - The for loop iterates over each item in the cars list.
      - For each iteration, the current item stored in the variable cars is printed
      - This loop will print each car in the list

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

      - Functions in Python are blocks of reusable code that perform a specific task. They allow encapsulation of code into a single unit, which can then be called and executed from various parts of your program

      Benefits:
       1. Reusability - Functions allow code to be written once and reused it multiple times, reducing redundancy.

       2. Modularity - Functions break code into smaller, manageable pieces, making it easier to read and maintain.

       3. Abstraction - Functions provide a way to abstract complex operations into simple function calls

       4. Testing and Debugging: Functions make it easier to test and debug individual components of codes.

       Example:
        def add_numbers(a,b)
            return a + b

         result = add_numbers(5, 3)
         print("The sum is:", result)

         Calling of function is done in this line: result = add_numbers(5, 3)

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

      1. A list is an ordered collection of items. A dictionary is an unordered collection of key-value pairs. 

      2. A list is defined using square brackets [] while a dictionary is defined using curly braces {} 

      3.  Elements in a list are accessed by their index which ina a deictionary elements are accessed by their keys.

      4. Lists are suitable for ordered collections of items, such as a sequence of numbers or strings while dictionaries are suitable for collections of related data that are labeled with unique keys, such as a set of attributes for an object.

      Example:

         # Create a list of numbers
         numbers = [1, 2, 3, 4, 5]

         # Create a dictionary with some key-value pairs
         person = {
            "name": "James",
            "age": 21,
            "city": "Nairobi"
         }
         # List
         # Accessing elements by index
         print("First number in the list:", numbers[0])
         print("Last number in the list:", numbers[-1])

         # Modifying an element
         numbers[2] = 10
         print("Modified list:", numbers)

         # Adding an element
         numbers.append(6)
         print("List after adding an element:", numbers)

         # Removing an element
         numbers.remove(4)
         print("List after removing an element:", numbers)

         # Dictionary
         # Accessing values by keys
         print("Name:", person["name"])
         print("Age:", person["age"])

         # Modifying a value
         person["age"] = 25
         print("Modified dictionary:", person)

         # Adding a key-value pair
         person["email"] = "jumesgathairu@gmail.com"
         print("Dictionary after adding a key-value pair:", person)

         # Removing a key-value pair
         del person["city"]
         print("Dictionary after removing a key-value pair:", person)



8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

      - Exception handling in Python is a way to manage errors or exceptional conditions that occur during the execution of a program. It enables one to ensure that a program continues to run even if an error occurs, and a meaningful error messages van be provided or perform clean-up operations.

      1. try - Contains code that might raise an exception.
               e.g try:
                       result = a / b

      2. except - Contains code to handle the exception if it occurs.
                  e.g except ZeroDivisionError as e:
                        print("Error: cannot divide by zero.")
                        result = None
      3. finally - Contains code that runs no matter what, whether an exception occurs or not.
                   e.g finally:
                           print("Execution of the divide_numbers function is complete.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

      - A module in Python is a file containing Python code that defines functions, classes, and variables, which can be imported and used in other Python scripts
         - One can import and use the functions and variables defined in a module using the import statement.

         MATH MODULE:
         import math

         number = 16
         result = math.sqrt(number)
         print("The square root is", result)

         num = 5
         fact = math.factorial(num)
         print("The factorial is", fact)

         radius = 3
         area = math.pi * (radius ** 2)
         print("The area of the circle is", area)

         ![alt text](<import math.png>)
         
      - A package is a collection of modules organized in directories that provide a hierarchical structure.


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

      - The open() function is used to read from and write to files.It returns a file object, which provides methods and attributes to interact with files.

      Reading from a file:
       1. Open the file in read mode
       2. Use read() to read the file's content.
       3.  Close the file using the close() method.

       Example:
         file_path = 'example.txt'

         try:
            with open(file_path, 'r') as file:
               content = file.read()
               print("File content:\n", content)
         except FileNotFoundError:
            print("The file was not found.")
         except IOError:
            print("An error occurred while reading the file.")


       Writting to a file:
        1. Open the file in write mode
        2. Use write() to write content to the file.
        3. Close the file using the close() method.

        Example:
         file_path = 'output.txt'
         lines_to_write = ["Line 1", "Line 2"]

         try:
            with open(file_path, 'w') as file:
               for line in lines_to_write:
                     file.write(line + '\n')
            print("Lines written to file successfully.")
         except IOError:
            print("An error occurred while writing to the file.")


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


