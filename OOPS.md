**OOPS**

**What is Object Oriented Programming (OOPs)?**

O*bject* O*riented* P*rogramming* (also known as OOPs) is a programming paradigm where the complete software is formed by objects which talk with each other.

**What is a Class?**

A **class** is a building block of Object-Oriented Programs. It is a user-defined data type that contains the data members and member functions that operate on the data members. It is like a blueprint or template of objects having common properties and methods.

**What is an Object?**

An **object** is an instance of a class. An object is a collection of data and the methods which operate on that data. Data members and methods of a class cannot be used directly. We need to create an object (or instance) of the class to use them. In simple terms, they are the actual world entities that have a state and behavior.

**What are the main features of OOPs?**

1. Encapsulation  
2. Data Abstraction  
3. Polymorphism  
4. Inheritance

**What is Encapsulation?**

Encapsulation is the binding of data and methods that manipulate them into a single unit such that the sensitive data is hidden from the users.

**What is Abstraction?**

Abstraction means showing only the necessary information and hiding the other irrelevant information from the user. Abstraction is implemented using classes and interfaces.

**What is Polymorphism?**

Polymorphism means some code to behave differently for different contexts.

**A) Compile-Time Polymorphism / Static polymorphism / Early binding**

The type of polymorphism where the binding of the call to its code is done at the compile time.

**B) Runtime Polymorphism** **/ Dynamic polymorphism / Late binding**

The type of polymorphism where the binding of the call to its code is done at the compile time runtime or execution.

![][image1]

**What is Inheritance? What is its purpose?**

The idea of inheritance is simple, a class is derived from another class and uses data and implementation of that other class.

**What are access specifiers? What is their significance in OOPs?**

Access specifiers are special types of keywords that are used to specify or control the accessibility of entities like classes, methods, and so on. **Private**, **Public**, and **Protected** are examples of access specifiers or access modifiers.

**Advantages of OOP**

1. OOP provides enhanced code reusability.  
2. The code is easier to maintain and update.  
3. It provides better data security.

**Disadvantages of OOP**

1. Proper planning is required because OOP can be a bit tricky.  
2. The OOP concept is not suitable for all kinds of problems.  
3. The length of the programs is much larger in comparison to the procedural approach, especially in cases of short programs.

**What other paradigms of programming exist besides OOPs?**

**1\. Imperative Programming Paradigm**

Imperative programming is about how to do things. It focuses on changing the program's state through specific instructions, telling the computer exactly what steps to follow to achieve a goal.

**Key Features:**

* **State Changes:** Programs are composed of a series of statements that change the program's state.  
* **Control Flow:** It involves sequences of commands (like loops and conditionals) to control the flow of execution.  
  **1.1**  **Procedural Programming**: Procedural programming is based on the concept of procedures (or functions). It structures the program as a series of steps or procedures to follow. **Examples**: C, Pascal, Fortran, BASIC

**1.2 Object-Oriented Programming (OOP):** OOP treats everything as an object that has properties (state) and methods (behavior). It organizes the program around these objects. **Examples: Java, C++, Python, Ruby**

**1.3 Parallel Programming:** Parallel programming involves breaking down tasks into smaller parts that can be executed simultaneously, improving efficiency and performance. **Examples: C (with OpenMP or MPI), Java (with concurrency libraries), Go, Erlang**

**2\. Declarative Programming Paradigm**

Declarative programming focuses on what to do rather than how to do it. You specify the desired outcome without explicitly detailing the steps to achieve it.

**Key Features:**

* **Logic Over Control Flow:** It expresses the logic of a computation without considering the control flow.  
* **Higher-Level Abstraction:** It allows for a higher level of abstraction than imperative programming.

**2.1 Logical Programming:** Logical programming is based on formal logic. You define facts and rules that express the relationships between data. **Examples**: Prolog, Mercury

**2.2 Functional Programming:** Functional programming creates programs by applying and composing functions. It emphasizes the use of pure functions without side effects. **Examples: Haskell, Lisp, Scala, F\#**

**2.3 Database Programming:** Database programming involves managing and manipulating data stored in databases. It utilizes specific programming models to interact with structured data. **Examples**: SQL, PL/SQL, T-SQL

**What is the difference between Structured Programming and Object Oriented Programming?**

| Object-Oriented Programming (OOP) | Structured Programming |
| :---- | :---- |
| OOP is based on objects that have state (attributes) and behavior (methods). | Structured programming focuses on the logical structure of a program, dividing it into functions and modules. |
| It follows a **bottom-up** approach, starting with defining objects and their interactions. | It follows a **top-down** approach, starting with a high-level overview and breaking it down into smaller parts. |
| Data flow is restricted to authorized parts of the program, enhancing data security. | There are no restrictions on data flow; any part of the program can access data freely. |
| Code reusability is achieved through inheritance and polymorphism, allowing the creation of new classes from existing ones. | Code reusability is achieved using functions and loops, but it's limited compared to OOP. |
| Methods can be dynamically called based on object behavior and runtime needs. | Functions are called sequentially, processing code step by step. |
| Modifying and updating code is generally easier due to encapsulation and abstraction. | Modifying code can be more challenging since changes may affect multiple parts of the program. |
| Emphasizes data as a core component, encapsulating it within objects. | Emphasizes the code logic and flow, often prioritizing procedures over data. |

 

**What is the difference between overloading and overriding?**

**Overloading:** Same method name, different parameter lists, occurs within the same class, resolved at compile time.

**Overriding:** Same method name and parameters, occurs between superclass and subclass, resolved at runtime.

**Operator Overloading:** Refers to giving additional meanings to standard operators when applied to user-defined types.

**Are there any limitations on Inheritance?**

* As it must pass through several classes to be implemented, inheritance takes longer to process.  
* If changes need to be made, they may need to be made in both base class and child class at the same time.  
* If inheritance is not implemented correctly, this could result in unforeseen mistakes or inaccurate outputs.

**What different types of Inheritance are there?**

| Inheritance Type | Java | Python | C++ |
| :---- | :---- | :---- | :---- |
| **Single Inheritance** | Yes | Yes | Yes |
| **Multilevel Inheritance** | Yes | Yes | Yes |
| **Hierarchical Inheritance** | Yes | Yes | Yes |
| **Multiple Inheritance** | Via interfaces | Yes | Yes |
| **Hybrid Inheritance** | Via interfaces | Yes | Yes |
| **Virtual Inheritance** | N/A | N/A | Yes (with virtual) |

**C++:** Error may occur when it inherits many different functions of same declaration from different classes.

**Python**: Supports multiple inheritance directly for classes, and method resolution is handled using the C3 linearization (MRO \- Method Resolution Order) which work like BFS. This resolving errors.

Link: [https://github.com/ParitKansal/OOPS/blob/main/Inheritance.md](https://github.com/ParitKansal/OOPS/blob/main/Inheritance.md)

**What is an interface?**

A unique class type known as an interface contains methods but not their definitions. Inside an interface, only method declaration is permitted. You cannot make objects using an interface.

Link \- [https://github.com/ParitKansal/OOPS/blob/main/interface.md](https://github.com/ParitKansal/OOPS/blob/main/interface.md)

**How is an abstract class different from an interface?**

| Abstract Class | Interface |
| :---- | :---- |
| Can have both abstract (pure virtual) and non-abstract (concrete) methods. | Can only have abstract (pure virtual) methods. |
| Can have final (constant), non-final, static, and non-static member variables. | Can only have static and final (constants) variables. |
| Does not support multiple inheritance in the same way as interfaces (C++ allows multiple inheritance, but with some complexities). | Supports multiple inheritance, allowing a class to implement multiple interfaces. |

 

**How much memory does a class occupy?**

A class itself occupies memory for its definition and any class-level attributes, but it doesn't allocate memory for instance variables until an object is created. Each instance of a class has its own memory for instance variables, while methods are shared among instances.

**Is it always necessary to create objects from class?**

**Creating Objects:** You must create objects to access non-static methods and variables.

**No Objects Needed:** You do not need to create objects to access static methods or variables; you can call them directly using the class name.

**What is the difference between a structure and a class in C++?**

| Feature | Class | Struct |
| :---- | :---- | :---- |
| **Default Access Specifier** | Private | Public |
| **Inheritance** | Default is private | Default is public |
| **Member Functions** | Can have member functions and can be abstract. | Can have member functions and can be abstract, but usually does not. |
| **Constructor/Destructor** | Can define constructors and destructors. | Can define constructors and destructors. |
| **Polymorphism / Virtual Function** | Supports polymorphism with virtual functions. | Supports polymorphism with virtual functions. |

 

**What is Constructor?**

A constructor is a block of code that initializes the newly created object. A constructor resembles an instance method but it’s not a method as it doesn’t have a return type. It generally is the method having the same name as the class but in some languages, it might differ like in python, a constructor is named **\_\_init\_\_.** 

**What are the various types of constructors in C++?**

The most common classification of constructors includes:

1. **Default Constructor**  
2. **Non-Parameterized Constructor**  
3. **Parameterized Constructor**  
4. **Copy Constructor**

**1\. Default Constructor**

The default constructor is a constructor that doesn’t take any arguments. It is a non-parameterized constructor that is automatically defined by the compiler when no explicit constructor definition is provided.

**2\. Non-Parameterized Constructor**

It is a user-defined constructor having no arguments or parameters.

**3\. Parameterized Constructor**

The constructors that take some arguments are known as parameterized constructors.

**4\. Copy Constructor**

A copy constructor is a member function that initializes an object using another object of the same class.

**Example:**

\`\`\`C++  
class base {  
    int a, b;  
    base(base& obj)  
    {  
        a \= obj.a;  
        b \= obj.b;  
    }  
}  
\`\`\`

**What is a destructor?**

A destructor is a method that is automatically called when the object is made of scope or destroyed.

In C++, the destructor name is also the same as the class name but with the (**\~**) **tilde symbol** as the prefix.

In Python, the destructor is named **\_\_del\_\_**.

In Java, the garbage collector automatically deletes the useless objects so there is no concept of destructor in Java. We could have used finalize() method as a workaround for the java destructor but it is also deprecated since Java 9\.

**Can we overload the constructor in a class?**

Yes We can overload the constructor in a class in Java. Constructor Overloading is done when we want constructor with different constructor with different parameter (Number and Type).

**Can we overload the destructor in a class?**

No, a destructor cannot be overloaded in a class. There can only be one destructor present in a class.

**Difference b/w Virtual Functions and Pure Virtual Functions**

| Feature | Virtual Functions | Pure Virtual Functions |
| :---- | :---- | :---- |
| **Definition** | A virtual function is a function that is used to override a method of the parent class in the derived class. | A pure virtual function, also known as an abstract function is a member function that doesn’t contain any statements.  |
| **Declaration** | Declared with the virtual keyword. | Declared with \= 0 to signify it is a pure virtual function. |
| **Implementation** | Can have an implementation in the base class, providing default behavior. | Must not have an implementation in the base class, enforcing derived classes to provide one. |
| **Instantiation** | Can instantiate the base class, allowing creation of base class objects. | Cannot instantiate the base class (it becomes abstract), ensuring that only derived classes can be instantiated. |
| **Example** | virtual double function () {return 0;} | virtual double function () const \= 0; |

 

[image1]: <data:image/png;base64,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>