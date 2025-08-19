📘 Classes and Objects in C++-

🎯 Aim-

To study and implement classes and objects in C++, understand the difference between inside and outside class definitions, and explore the role of public and private access specifiers in encapsulation.

📚 Theory-

In C++, classes and objects are the foundation of Object-Oriented Programming (OOP).

🏗️ Class-

A class is a blueprint that defines data members (variables) and member functions (methods).

Access specifiers:

public → Accessible outside the class.

private → Accessible only inside the class.

Supports encapsulation (data hiding).

🧑‍🤝‍🧑 Object-

An object is an instance of a class.

Each object has its own copy of class variables.

📋 Algorithms-

🔹 Cube Volume (Outside Class)-

Start

Define class Cube with private members: side, volume.

Declare public functions: input(), calculateVolume(), output().

In input() → take user input for side.

In calculateVolume() → compute volume = side * side * side.

In output() → display volume.

In main() → create object c2, call functions.

End

🔹 Cuboid Volume (Inside Class)-

Start

Define class Cuboid with members: length, breadth, height, volume.

Create input() to take dimensions.

Create Volume() → volume = length * breadth * height.

Create Output() → print volume.

In main() → create object v1, call functions.

End

🔹 Reverse Array (Outside Class)-

Start

Define class ArrayOps with function reverseArray(arr[], size).

In function → loop from size-1 down to 0 and print elements.

In main() → declare arr[] = {10, 20, 30, 40, 50}, find size, create object, call function.

End

🔹 Simple Calculator-

Start

Define class Calculator with members num1, num2.

Create functions:

add() → print sum

subtract() → print difference

multiply() → print product

divide() → if num2 != 0, print division else error

In main() → create object c, take input, call all functions.

End

🔹 Student Details-

Start

Define class Student with members: name, branch, subject, year, result.

In main() → create objects S1, S2, S3.

Assign values, e.g., S1.name = "Anavi Kashyup";.

Print student details.

End

🧠 Conclusion-

This experiment demonstrates the importance of Classes and Objects in C++.

🏗️ Class → Defines structure and behavior.

🧑‍🤝‍🧑 Object → Real entity with data and functionality.

✅ Key Insights:-

Use inside class methods for simplicity.

Use outside class methods for better organization.

Classes and objects enable encapsulation, reusability, and real-world modeling in programming.

Example: Car c1; creates an object c1 of class Car.


Inside the class → Function body is written directly inside the class.

Outside the class → Function declared inside but defined outside using :: (scope resolution operator).
