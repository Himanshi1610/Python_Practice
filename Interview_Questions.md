## 1. What is the difference between Python Arrays and lists?
### Arrays and lists, in Python, have the same way of storing data. But, arrays can hold only a single data type elements whereas lists can hold any data type elements.
-------
## 2. How can you randomize the items of a list in place in Python?
### By using shuffle function from random module.
------
## 3. What is pickling and unpickling?
### Pickle module accepts any Python object and converts it into a string representation and dumps it into a file by using dump function, this process is called pickling. While the process of retrieving original Python objects from the stored string representation is called unpickling.
------
## 4. What are docstrings in Python?
### Docstrings are not actually comments, but, they are documentation strings. These docstrings are within triple quotes. They are not assigned to any variable and therefore, at times, serve the purpose of comments as well.
------
## 5. Whenever Python exits, why isn’t all the memory de-allocated?
### Whenever Python exits, especially those Python modules which are having circular references to other objects or the objects that are referenced from the global namespaces are not always de-allocated or freed.
### It is impossible to de-allocate those portions of memory that are reserved by the C library.
### On exit, because of having its own efficient clean up mechanism, Python would try to de-allocate/destroy every other object.
------
## 6. How can the ternary operators be used in python?
### The Ternary operator is the operator that is used to show the conditional statements. This consists of the true or false values with a statement that has to be evaluated for it.
### The Ternary operator will be given as: [on_true] if [expression] else [on_false]x, y = 25, 50big = x if x < y else y
------
## 7. What does this mean: *args, **kwargs? And why would we use it?
### We use *args when we aren’t sure how many arguments are going to be passed to a function, or if we want to pass a stored list or tuple of arguments to a function. **kwargs is used when we don’t know how many keyword arguments will be passed to a function, or it can be used to pass the values of a dictionary as keyword arguments. The identifiers args and kwargs are a convention, you could also use *bob and **billy but that would not be wise.
------
## 8. Explain split(), sub(), subn() methods of “re” module in Python.
### split() – uses a regex pattern to “split” a given string into a list.
### sub() – finds all substrings where the regex pattern matches and then replace them with a different string
### subn() – it is similar to sub() and also returns the new string along with the no. of replacements.
------
## 9. How can files be deleted in Python?
### To delete a file in Python, you need to import the OS Module. After that, you need to use the os.remove() function.
------
## 10. Does Python have OOps concepts?
### Python is an object-oriented programming language. This means that any program can be solved in python by creating an object model. However, Python can be treated as procedural as well as structural language.
------
## 11.  What is the difference between deep and shallow copy?
### Shallow copy is used when a new instance type gets created and it keeps the values that are copied in the new instance. Shallow copy is used to copy the reference pointers just like it copies the values. These references point to the original objects and the changes made in any member of the class will also affect the original copy of it. Shallow copy allows faster execution of the program and it depends on the size of the data that is used.
### Deep copy is used to store the values that are already copied. Deep copy doesn’t copy the reference pointers to the objects. It makes the reference to an object and the new object that is pointed by some other object gets stored. The changes made in the original copy won’t affect any other copy that uses the object. Deep copy makes execution of the program slower due to making certain copies for each object that is been called.
------
## 12. How is Multithreading achieved in Python?
### Python has a multi-threading package but if you want to multi-thread to speed your code up, then it’s usually not a good idea to use it.
Python has a construct called the Global Interpreter Lock (GIL). The GIL makes sure that only one of your ‘threads’ can execute at any one time. A thread acquires the GIL, does a little work, then passes the GIL onto the next thread.
### This happens very quickly so to the human eye it may seem like your threads are executing in parallel, but they are really just taking turns using the same CPU core.
### All this GIL passing adds overhead to execution. This means that if you want to make your code run faster then using the threading package often isn’t a good idea.
------
## 13. What is Polymorphism in Python?
### Polymorphism means the ability to take multiple forms. So, for instance, if the parent class has a method named ABC then the child class also can have a method with the same name ABC having its own parameters and variables. Python allows polymorphism.
------
## 14. Define encapsulation in Python?
### Encapsulation means binding the code and the data together. A Python class in an example of encapsulation.
------
## 15. How do you do data abstraction in Python?
### Data Abstraction is providing only the required details and hiding the implementation from the world. It can be achieved in Python by using interfaces and abstract classes.
------
## 16. How to create an empty class in Python? 
### An empty class is a class that does not have any code defined within its block. It can be created using the pass keyword. However, you can create objects of this class outside the class itself. IN PYTHON THE PASS command does nothing when its executed. it’s a null statement. 
### class a:
###   &amp;amp;amp;nbsp; pass
### obj=a()
### obj.name="xyz"
### print("Name = ",obj.name)
### OUTPUT: Name =  xyz
------
## 17. Write a program in Python to produce Star triangle.
### def pyfunc(r):
###     for x in range(r):
###         print(' '*(r-x-1)+'*'*(2*x+1))    
### pyfunc(9)
------
## 18. What is the maximum possible length of an identifier?
### Identifiers can be of any length.
------
## 19. When will the else part of try-except-else be executed?
### When no exception occurs. The else part is executed when no exception occurs.
------
## 20. To open a file c:scores.txt for writing, we use?
### outfile = open(“c:scores.txt”, “w”)
------
