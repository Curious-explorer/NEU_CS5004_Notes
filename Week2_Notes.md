**Notes -**
1. How to write methods in a class?
  - Define what is the method for. (Simple 1 line comments)
  - Convert that informal statement of purpose to a more formalized description. (Javadoc comments and method definition, and a normal return statement)(the code area is still blank)
  - Create a set of tests that describe what the method should produce if it's functioning correctly. (Write tests before code)
  - Write the code that implements the method's functionality. (writing actual code) (Which we usually do first, but it is wrong way)
  - Even during writing the method code, try to write comments of what you have and what you want, this will make you focus on task at hand.
  - Document all your design elements as you go along. (Do not make the same mistake made in python)
2. We need to implement test drive software development model simply because, when we develop the code first, we know where the weak points of the code are and we are biased towards not writing test cases which will exploit those weaknesses.
3. Every method definition consists of the following parts:

    - A purpose statement. This consists of a single sentence that describes the purpose of this method. A longer description of the method may follow.
    - The type of the value returned from the method, known as the return type
    - The method name, where the standard naming convention starts with a lowercase letter and uses ''camelCase" to distinguish words within the name
    - A parenthesized argument list, consisting of the type and name of each argument, separated by commas
    - The method body, surrounded by braces; this is the code to execute when the method is invoked
4. The **signature** of a Java method is name of the method and its list of parameter types. The access specifier and return type are part of the **method declaration** . This subtle difference may not seem significant, but when we learn about method overloading it becomes quite important since methods are **overloaded** by signature, not return type or access specifier.
5. Function overloading can be used in order to implement certain function which might be tested for different arguments with different data-types, so rather than writing a big code in which we compare, which data-type input has, we can just use function-overloading to seperate the conditions.
6. Object variables are decleared private, because the function acting on the objects is not supposed to access them, rather attributes should be accessed through **getters** which are public in nature.
7. **No matter how small things feel, you should seperate them using methods, because we want single point of maintainace in our code. This is major point as the checking will ensure you understood this correctly.**
8. Java has several inbuilt exception types, which are all classes. Exceptions provide us with a way to handle errors . Follow this procedure when you write a new method:

    - Write the purpose statement
    - Write a method signature
    - Using the template write the method body so that it works correctly under ideal circumstances .
    - Carefully think about all situations that can occur, other than ideal circumstances . This includes possibly invalid inputs, invalid computations or results. These are possible errors.

    - For each error:

    - If there is a way to prevent the error from happening, do it. This is the best kind of error handling. Else go to the next step.
    - If there is a way to recover from the error in this method itself, do it. There is no need to use exceptions as the recovery happens in the same method as the error. Else go to the next step.
    - Choose an appropriate exception type for the error. Declare that this method throws this exception in its signature, and throw this exception appropriately.

9. @Test(expected = IllegalArgumentException.class) this is how to expect if any test is supposed to be resulting in an Exception. 
10. Cool resource - 
