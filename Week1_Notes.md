## Notes -
1. Computers do not work with information: they work with data , which is a way to represent information that makes it ''convenient" to use.
2. Information like Book A is written by author XYZ. Or "it is 75 degrees Farenheit outside"
3. Data is straightforward.
4. **Variables** are named locations in the memory where you can store data! ...So in a way you can say variables are memory addresses where we store the data.
5. In java, char are stored in ' ' (single quotes), and string is stored in " " (double quotes).
6. Learn about the basic OO principles more carefully!
7. Why do you think String is capitalized in Java? - because it is a class, and it is common programming style to make the first letter of a class uppercase.
8. Naming: class names in Java always are written in TitleCase, and field names are always written in camelCase. Primitive type names, like int and boolean , are lowercase.
9. Comments: a multi-line comment can be enclosed between /* and */ as shown. A single-line comment starts with //
10. If we name the class Person then it is saved in a file Person.java . This allows us to divide our code in meaningful chunks, although one-class-per-file is not strictly enforced.
11. This JUnit test class executes in the following manner:
    - The method annotated with @Before is executed before each method annotated with @Test.
    - By default, a method annotated with @Test passes. If the expected and actual values of an assertEquals method are equal to each other, then the program moves on to the next statement in the method. If they are not equal, the method aborts and the test is said to fail .
    - Irrespective of the result of a test method (pass or fail) it moves on to the next test method, until all the test methods are run exactly once.
    - Hence it is recommended to have one type of tests in one test method.

12. How does one decide whether to make something private or public ? The following rules are useful and apply well in most cases:

    - Make all fields private .
    - Make all constructors public .
    - Make a method public only if you can think of at least one situation where the method must be called from outside this class. Else make it private

13. Commenting and Documentation

It is a really good idea to write comments explaining your design and purpose. This allows you and anybody other using your code to understand what it is doing, how to use it and how it has been designed and implemented.

It is a good idea to abide by the following conventions:

    Above the class definition, explain in 1-2 sentences what this class represents. This explanation should include both semantic details (e.g. what the class represents from the problem statement) and technical details (e.g. useful for a fellow designer/programmer). Also mention any details that a user of this class may need to know to use it appropriately.
    Before each method (including the constructor and getters ) write the purpose statement for the method. Also include a list of any arguments along with what they represent, and what the method returns.
    Within the method body mention any details that you think are relevant to what that method is doing.

A good rule of thumb is to assume that the audience for your comments is not you, but other designers/programmers who will use your code. If the language is such that only you can understand it fully (because you implemented it) revise the comments.
14. Documentation -

    - All comments beginning with /** are Javadoc-style comments. These are the only comments that the Javadoc tool will read.
    - Every line of such comments begins with * followed by a space.
    - @param denotes information about a method argument.
    - @return denotes information about whatever the method returns.

Note again that since everything is within Java comments, this documentation does not affect your Java source code in any way. 

We strongly recommend developing the habit of writing comments in Javadoc style to facilitate creating neat documentation.

    Note that Javadoc-style documentation is ''public-facing." That is, this documentation is meant for others , not just yourself.
    
15. In a class diagram, and is very useful in creating and understanding design visually. + denotes public, - denotes private, and the arrow denotes the has-a relationship. 
