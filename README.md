# Software Development Level 4 - KM2 PreCourse Tasks

These 5 projects were assigned by the course Tutor, and were to be completed ready for the KM2 course start.

Below are the task objectives.


# Pre-Course Assessment
Instructions:
For each of the project below you are to create the requested program.
Your solutions are to be emailed as a word document either as screen shots of the code (must be legible) or copy and paste the code. Also include screen shots of your code executing.
Project 1: Converting a Decision Table into a Program
You are developing an invoicing application that calculates discount percentages based on the quantity of a product purchased. The logic for calculating discounts is listed in the following decision table. If you need to write a C# method that uses the same logic to calculate the discount, how would you write such a program? The user inputs the quantity and the discount is displayed.  Produce this program in any programming language.

Quantity < 10	Y	N	N	N
Quantity < 50	Y	Y	N	N
Quantity < 100	Y	Y	Y	N
Discount	5%	10%	15%	20%

**Project 2:** Creating a Maths Function
You are developing a library of mathematical functions. You are to write a program containing the function to calculate the factorial value of an integer input by the user. The user inputs an integer value and its factorial value is displayed. Extension: Re-write this function as a recursive function.

**Project 3:** Handling Exceptions
You are writing code for a simple arithmetic library. You decide to create a method named Divide that takes two arguments, x and y, and returns the value of x/y. You need to catch any arithmetic exceptions that might be thrown for errors in arithmetic, casting, or data type conversions. You also need to catch any other exceptions that may be thrown from the code. To address this requirement, you need to create properly structured exception-handling code. How would you write such a program? 

**Project 4:** Creating Properties
You need to create a class named Product that represents a product. The class has a single property named Name. Users of the Product class should be able to get and set the value of the Name property. However, any attempt to set the value of Name to an empty string or a null value should raise an exception. Also, users of the Product class should not be able to access any other data members of the Product class. How will you create such a class?

**Project 5:** Overriding the ToString Method
You are writing code for a Product class. The Product class contains the name and price of a product. You need to override the base class (System.Object) method ToString to provide information about the objects of the product class to the calling code. So the method will output a message such as
	The product is productName and costs productPrice
What code do you need to write for the Product class in order to meet this requirement?
