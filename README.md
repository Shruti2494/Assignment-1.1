# Assignment-1.1

Data Types:

Q1.) What are custom data types in Python, and how are they created?
Answer: Custom data types are user-defined classes. You can create them by defining a class and its attributes and methods.

Q2.) Explain the difference between deep and shallow copy in Python. When is each used?
Answer: A shallow copy creates a new object but references the elements within. A deep copy creates a new object with new elements. Use shallow copies for efficiency and deep copies when you want to isolate objects.

Q3.)What is a generator in Python, and how does it differ from a regular function?
Answer: A generator is a function that yields values one at a time using the yield keyword. It's memory-efficient and allows you to iterate over large data sets.

Q4.)What is a named tuple, and when would you use it in Python?
Answer: A named tuple is a subclass of a tuple with named fields. It's useful when you want to access elements by name instead of index.


Operators:

Q1.) Explain operator overloading in Python and provide an example.
Answer: Operator overloading allows you to define custom behavior for operators in your classes. For example, you can define how the + operator works for instances of your class.

Q2.) What are the differences between the is and == operators for comparing objects?
Answer: is checks if two objects are the same in memory, while == checks if their values are equal. For user-defined objects, you can customize == using the __eq__ method.

Q3.) How can you use the with statement in Python, and what is its purpose?
Answer: The with statement is used for context management. It ensures that resources are acquired and released properly, for example, when working with files using open.

Q4.) Explain how operator chaining works in Python, and provide an example.
Answer: Operator chaining allows you to chain multiple comparisons in a single expression, making code more concise. For example, 1 < x < 10 checks if x is between 1 and 10.


Conditional Statements:

Q1.) What are decorators in Python, and how are they used to modify functions?
Answer: Decorators are functions that modify the behavior of other functions. They are commonly used for tasks like logging, authentication, or performance monitoring.

Q2.) Explain how to handle exceptions with the try, except, else, and finally blocks.
Answer: The try block contains code that might raise an exception. except handles specific exceptions, else is executed if no exceptions occur, and finally is executed regardless of exceptions.

Q3.) What is a lambda function in Python, and when is it used?
Answer: A lambda function is an anonymous, one-liner function used for simple operations. It's often used when a small function is needed temporarily.

Q4.) How can you create a custom exception in Python, and what is its purpose?
Answer: You can create a custom exception by defining a new class that inherits from the built-in Exception class. Custom exceptions allow you to handle specific errors in a more descriptive way.


Looping Statements:

Q1.) Explain list comprehensions and when they are preferred over traditional loops.
Answer: List comprehensions provide a concise way to create lists. They are preferred for simple operations and can make code more readable.

Q2.) What is a generator expression in Python, and how does it differ from a list comprehension?
Answer: A generator expression is similar to a list comprehension but generates values on-the-fly, making it memory-efficient for large datasets.

Q3.) What is the purpose of the async and await keywords in Python, and how do they relate to asynchronous programming?
Answer: async and await are used for asynchronous programming. They allow you to write non-blocking code, improving performance for I/O-bound tasks.

Q4.) Explain the Global Interpreter Lock (GIL) in Python and its impact on multi-threading.
Answer: The GIL restricts multiple threads from executing Python code concurrently. It can limit the benefits of multi-threading for CPU-bound tasks but doesn't affect multi-processing.


Functions:

Q1.) How does the *args and **kwargs syntax work in Python function parameters?
Answer: *args allows a function to accept a variable number of non-keyword arguments as a tuple. It collects all extra positional arguments passed to the function.
**kwargs allows a function to accept a variable number of keyword arguments as a dictionary. It collects all extra keyword arguments passed to the function.

Q2.)How does variable scope work in Python, and what is the global keyword used for in functions?
Answer: Python uses the LEGB (Local, Enclosing, Global, Built-in) rule to determine the scope of variables. Local variables are defined within the function, enclosing variables are from an outer function (if nested), global variables are defined at the module level, and built-in variables are part of Python's standard library.
The global keyword in functions is used to declare a variable as global, allowing it to be modified within the function while affecting its value outside the function's scope.

Q3.) What is the difference between a function and a method in Python?
Answer: In Python, both functions and methods are blocks of code that perform specific tasks. The key difference is that functions are standalone and do not belong to any specific object or class, 
while methods are associated with objects and classes. Functions can be called directly, but methods are called on objects, typically using dot notation.

Q4.) What is the difference between arguments and parameters in a Python function?
Answer: Parameters are the variables listed in the function's definition and act as placeholders for values that will be passed when the function is called.
Arguments are the actual values that are passed to the function when it is invoked. They replace the corresponding parameters within the function's execution.
