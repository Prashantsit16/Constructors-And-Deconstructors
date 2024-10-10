# Constructors-And-Deconstructors
AIM:-
Constructors and destructors in C++

Software used:-
VS code

Theory:-
Constructor
A constructor in C++ is a special member function that is used to initialize the variables of a class when an object is created.

Key Features
Name Matching: The constructor's name matches exactly with the class name.
No Return Type: Constructors do not have a return type, not even void.
Automatic Invocation: A constructor is automatically invoked when an object of the class is instantiated.
Initialization: Primarily used to initialize member variables of the class.
Access Control
Public Section: Constructors are typically declared in the public section of a class to allow easy creation of objects.
Private or Protected Sections: Can also be declared in the private or protected sections to restrict object creation.
Constructor Overloading
Multiple Constructors: Constructors can be overloaded, allowing multiple ways of initializing an object. Restrictions: Constructors cannot be declared as virtual functions.

Types of constructors:
Default constructor : A default constructor is a constructor that takes no parameters or has all default arguments. If no constructor is explicitly defined, C++ automatically provides a default constructor. It initializes the class's members with default values (for built-in types) or calls their default constructors (for other objects).
Parameterized constructor: A parameterized constructor allows arguments to be passed when an object is created. This constructor initializes object attributes with specific values provided by the user. It enables flexibility in object creation by allowing different initialization based on the passed parameters.
Copy constructor: A copy constructor creates a new object as a copy of an existing object. It takes a reference to an object of the same class as its parameter and duplicates the attributes of the given object. The copy constructor is called when an object is passed by value, returned by value, or explicitly copied. It ensures that the new object has the same state as the copied object.
Syntax:-
Inside Class Definition:

ClassName(parameters) { 
    // implementation 
}
Destructor
A destructor is a special member function that is automatically called when an object goes out of scope or is explicitly deleted. The destructor has the same name as the class, preceded by a tilde (~), and it has no return type or parameters. Destructors are primarily used to release resources, such as memory or file handles, ensuring that objects clean up after themselves when they are no longer needed.

Output:
1. Default constructor:![Screenshot 2024-10-10 133336](https://github.com/user-attachments/assets/85f3a45a-944c-4485-9718-ae500decc703)


2.Parameterized constructor:![Screenshot 2024-10-10 132848](https://github.com/user-attachments/assets/95065ffe-0ea8-4a4d-b3e2-5f17f6a18988)

3.Copy constructor:![Screenshot 2024-10-10 132812](https://github.com/user-attachments/assets/f320bfa4-faf0-432f-8399-8168a6697c0a)

4.Constructor with arguements:![Screenshot 2024-10-10 132744](https://github.com/user-attachments/assets/eaa29f41-f3b8-433f-b95d-d27c0303299e)

5.Constructor:![Screenshot 2024-10-10 133312](https://github.com/user-attachments/assets/d3fe9926-d6c2-4829-ad8b-07ae6e5cbe17)

6.Destructor:![Screenshot 2024-10-10 135112](https://github.com/user-attachments/assets/6dfc7a05-b15d-4c19-920d-62751c98f5a9)

Conclusion:
We learned how to implement constructors and destructors in C++.


