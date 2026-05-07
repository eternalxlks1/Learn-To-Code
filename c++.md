```c++
// Introduction to C++

#include <iostream> // Header file for input/output
using namespace std; // Allows using standard namespace

// Main function - the starting point of any C++ program
int main() {
    // 1. Output to the console
    cout << "Hello, World!" << endl;

    // 2. Variables and Data Types
    int age = 25;          // Integer
    double pi = 3.14159;   // Double (floating-point number)
    char grade = 'A';      // Character
    string name = "Alice"; // String
    bool isStudent = true; // Boolean

    // Displaying variable values
    cout << "Name: " << name << ", Age: " << age << endl;

    // 3. Control Structures
    if (age > 18) {
        cout << "You are an adult." << endl;
    } else {
        cout << "You are a minor." << endl;
    }

    for (int i = 0; i < 5; i++) {
        cout << "Iteration: " << i << endl;
    }

    // 4. Functions
    // Declaring and calling a function
    int add(int a, int b); // Function prototype
    cout << "Sum: " << add(5, 3) << endl;

    // 5. Arrays
    int numbers[3] = {1, 2, 3};
    for (int i = 0; i < 3; i++) {
        cout << "Array element: " << numbers[i] << endl;
    }

    // 6. Pointers
    int value = 42;
    int* ptr = &value; // Pointer to the variable 'value'
    cout << "Pointer value: " << *ptr << endl; // Dereferencing pointer

    // 7. Classes and Objects
    class Person {
    public:
        string name;
        int age;

        void introduce() {
            cout << "Hi, I'm " << name << " and I'm " << age << " years old." << endl;
        }
    };

    Person person;
    person.name = "Alice";
    person.age = 25;
    person.introduce();

    return 0;
}

// Function definition
int add(int a, int b) {
    return a + b;
}

```c++
