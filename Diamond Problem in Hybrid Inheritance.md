# Diamond Problem in Hybrid Inheritance

### Code
```C++
#include <iostream>

// Base class
class A {
public:
    void displayA() {
        std::cout << "Class A" << std::endl;
    }
};

// Intermediate class derived from Base class A
class B : public A {
public:
    void displayB() {
        std::cout << "Class B" << std::endl;
    }
};

// Another Intermediate class derived from Base class A
class C : public A {
public:
    void displayC() {
        std::cout << "Class C" << std::endl;
    }
};

// Derived class using multiple inheritance from B and C
class D : public B, public C {
public:
    void displayD() {
        std::cout << "Class D" << std::endl;
    }
};

int main() {
    D obj;

    // Access methods from different base classes
    obj.displayB();  // From class B
    obj.displayC();  // From class C
    obj.displayD();  // From class D

    // Ambiguity arises here because both B and C inherit from A
    // This causes ambiguity: which displayA() to call?
    obj.displayA();  

    return 0;
}
```

#### Output:

```Output
ERROR!
/tmp/URFRpemY87.cpp: In function 'int main()':
/tmp/URFRpemY87.cpp:45:9: error: request for member 'displayA' is ambiguous
   45 |     obj.displayA();
      |         ^~~~~~~~
/tmp/URFRpemY87.cpp:6:10: note: candidates are: 'void A::displayA()'
    6 |     void displayA() {
      |          ^~~~~~~~
/tmp/URFRpemY87.cpp:6:10: note:                 'void A::displayA()'
```
-------

## Using Virtual Inheritance

### Code
```C++
#include <iostream>

// Base class with virtual inheritance
class A {
public:
    void displayA() {
        std::cout << "Class A" << std::endl;
    }
};

// Intermediate classes use virtual inheritance from A
class B : virtual public A {
public:
    void displayB() {
        std::cout << "Class B" << std::endl;
    }
};

class C : virtual public A {
public:
    void displayC() {
        std::cout << "Class C" << std::endl;
    }
};

// Derived class inherits from B and C
class D : public B, public C {
public:
    void displayD() {
        std::cout << "Class D" << std::endl;
    }
};

int main() {
    D obj;

    obj.displayB();  // From class B
    obj.displayC();  // From class C
    obj.displayD();  // From class D
    obj.displayA();  // Now works correctly due to virtual inheritance

    return 0;
}
```

#### Output
```output
/tmp/RuDCeEhFjF.o
Class B
Class C
Class D
Class A
```