MODULE 3

This repository contains simple, concept-based Java programs demonstrating how different operators and control statements work in Java.
Each program uses user input and provides clear console output examples for better understanding.

📘 Overview
#	Program Title	Concept Covered
1	Arithmetic Operators	+, −, ×, ÷, %
2	Bitwise Operators	AND, OR, XOR
3	Relational Operators	Comparisons (>, <, ==)
4	Logical Operators	AND / OR Conditions
5	Assignment Operators	+=, −=, ×=
6	Ternary Operator	Conditional Expression
7	Selection Statements	if–else Decision Making
8	Iteration Statements	for Loop
9	Jump Statements	continue Statement
🧩 Program Details
1️⃣ Arithmetic Operators
Description: Performs arithmetic operations on two integers.

Enter two integers: 20 6 Sum = 26 Difference = 14 Product = 120 Quotient = 3 Remainder = 2

2️⃣ Bitwise Operators
Description: Demonstrates bitwise AND, OR, and XOR on user-entered integers.

Enter two integers: 5 3 a & b = 1 a | b = 7 a ^ b = 6

3️⃣ Relational Operators
Description: Compares two numbers and prints which is greater or if they are equal.

Enter two numbers: 10 20 20 is greater than 10

4️⃣ Logical Operators
Description: Checks if a person is eligible to vote based on age and citizenship.

Enter your age: 20 Are you a citizen? (true/false): true Eligible to vote.

5️⃣ Assignment Operators
Description: Demonstrates the use of +=, -=, and *= operators.

Enter an integer: 10 After += : 15 After -= : 13 After *= : 39

6️⃣ Conditional (Ternary) Operator
Description: Uses the ternary operator to determine if a number is even or odd.

Enter a number: 7 7 is Odd

7️⃣ Selection Statements (if–else)
Description: Determines whether the number is positive, negative, or zero.

Enter a number: -5 Negative

8️⃣ Iteration Statements (for loop)
Description: Prints the multiplication table for any user-entered number.

Enter a number: 4 Multiplication Table of 4: 4 x 1 = 4 4 x 2 = 8 ... 4 x 10 = 40

9️⃣ Jump Statements (continue)
Description: Prints numbers 1–10 but skips the number 5 using the continue statement.

1 2 3 4 6 7 8 9 10


MODULE 4
This repository also contains Java programs that demonstrate the principles of Object-Oriented Programming (OOP) — specifically inheritance, method overriding, and hierarchical relationships between classes.

Each program is designed to clearly show how classes and objects interact through inheritance and polymorphism.

📘 Overview
#	Program Title	Concept Covered
1	Employee → Manager	Single Inheritance
2	Shape → Circle, Rectangle	Hierarchical Inheritance & Method Overriding
3	Transport → Bus, Truck	Hierarchical Inheritance
4	Doctor → Dentist, Cardiologist, Surgeon	Method Overriding / Polymorphism
🧩 Program Details
1️⃣ Employee → Manager (Single Inheritance)
Description:
Demonstrates single inheritance — the subclass Manager inherits attributes and methods from the base class Employee.

Output Example:

Enter manager name: Talha Enter salary: 65000 Enter department: Physics

--- Employee Info --- Name: Talha Salary: 65000.0 Department: Physics

2️⃣ Shape → Circle, Rectangle (Hierarchical Inheritance)
Description:
Shows hierarchical inheritance where multiple subclasses (Circle, Rectangle) extend a common base class Shape.
Each subclass overrides the displayShape() method and has its own area() method.

Output Example:

Enter circle radius: 5 This is a Circle. Circle area = 78.53981633974483

Enter rectangle length: 6 Enter rectangle width: 4 This is a Rectangle. Rectangle area = 24.0

3️⃣ Transport → Bus, Truck (Hierarchical Inheritance)
Description:
Illustrates hierarchical inheritance again — both Bus and Truck extend Transport.
Each subclass adds its own functionality, demonstrating method extension.

Output Example:

Enter number of passengers for bus: 45 Transport is moving. Bus carrying 45 passengers.

Enter goods weight in tons for truck: 12 Transport is moving. Truck carrying 12.0 tons of goods.

4️⃣ Doctor → Dentist, Cardiologist, Surgeon (Method Overriding)
Description:
Demonstrates runtime polymorphism by overriding the consultationFee() method in each subclass.
The correct method is called depending on the object type created.

Output Example:

Choose doctor type:

1.Dentist

2.Cardiologist

3.Surgeon Enter choice (1-3): 2 Consultation Fee: ₹1200.0

⚙️ How to Run the Programs
Save each code in a separate .java file with the same class name.
Open a terminal in the folder location.
Compile the program using:
javac FileName.java
java FileName
