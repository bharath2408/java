# JAVA

## What is java?

- Java is a high level programming language.
- It deals with object so we can also call it as object
oriented programming language.
- Java is platform independent but depends on JVM.
- It is a 2 step compilation process.

## why Java is called as platform independent language ?

- I can create a source file in one platform with the help of its
.class file I can run it in any platform so it is called as platform
independent language.

## List the features of Java ?

1. Simple

- Java is very easy to learn, and its syntax is simple, clean
and easy to understand. According to Sun Microsystem,
Java language is a simple programming language
because:

- Java syntax is based on C++ (so easier for
programmers to learn it after C++).

- Java has removed many complicated and rarely-used
features, for example, explicit pointers, operator
overloading, etc.

- There is no need to remove unreferenced objects
because there is an Automatic Garbage Collection in
Java.

2. Object-oriented

- Java is an object-oriented programming language.
Everything in Java is an object. Object-oriented means
we organize our software as a combination of different
types of objects that incorporate both states and
behavior.

- Object-oriented programming (OOPs) is a methodology
that simplifies software development and maintenance
by providing some rules.

Basic concepts of OOPs are:
1. Object
2. Class
3. Inheritance
4. Polymorphism
5. Abstraction
6. Encapsulation

3. Platform Independent

- Java is platform independent
- Java is platform independent because it is different from
other languages like C, C++, etc. which are compiled
into platform specific machines while Java is a write
once, run anywhere language. A platform is the
hardware or software environment in which a program
runs.

- There are two types of platforms software-based and
hardware-based. Java provides a software-based
platform.

- The Java platform differs from most other platforms in
the sense that it is a software-based platform that runs
on top of other hardware-based platforms. It has two
components:

- Runtime Environment
- API(Application Programming Interface)
- Java code can be executed on multiple platforms, for
example, Windows, Linux, Sun Solaris, Mac/OS, etc.
Java code is compiled by the compiler and converted
into bytecode. This bytecode is a platform-independent
code because it can be run on multiple platforms, i.e.,
Write Once and Run Anywhere (WORA).

4. Secured

Java is best known for its security. With Java, we can develop
virus-free systems. Java is secured because:

- No explicit pointer
- Java Programs run inside a virtual machine sandbox

5. Robust
The English meaning of Robust is strong. Java is robust
because:

- It uses strong memory management.
- There is a lack of pointers that avoids security problems.
- Java provides automatic garbage collection which runs
on the Java Virtual Machine to get rid of objects which
are not being used by a Java application anymore.
- There are exception handling and the type checking
mechanism in Java. All these points make Java robust.

6. Portable

Java is portable because it facilitates you to carry the Java
bytecode to any platform. It doesn't require any implementation.

7. Multi-threaded

A thread is like a separate program, executing concurrently. We
can write Java programs that deal with many tasks at once by
defining multiple threads. The main advantage of
multi-threading is that it doesn't occupy memory for each
thread. It shares a common memory area. Threads are
important for multi-media, Web applications, etc.

8. High-performance

Java is faster than other traditional interpreted programming
languages because Java bytecode is "close" to native code. It
is still a little bit slower than a compiled language (e.g., C++).
Java is an interpreted language that is why it is slower than
compiled languages, e.g., C, C++, etc.

## What is JVM ? Why is Java called the Platform Independent.

It is whole responsible to execute the java program. JRE is
installed in each and every electronics device and .class file
can be executed on any electronic device , hence Java is
platform independent.

## What is the Difference between JIT , JDK and JRE ?
JIT is whole responsible to convert . class file to binary format.
JDK is whole responsible to execute the java program.
JRE is an environment setup provided to run the java program.
What is file?
File is a container which is used to store some data
permanently.
What is source file?
Source file is nothing but a container where programs are
returned in high-level language.
What is executable file?
Executable file is a file which is created by the java source file
and is also called as .class file or byte code file.
What is the executable file of java source file?
.class file is the executable file of java source file.
What is compile time?
Once the compiler accept the source file it will perform some
task such as:
● Check the syntax
● Check the symmantics
● Add some instructions
The overall time taken by the compiler to do these process and
generate executable .class file is called as compile time.
Difference between print & println statement?
print println
We cannot use print
statement without passing
the data.
We can use println statement
without passing the data.
If we want to print output in
the same line we will use
print statement.
After printing the data cursor will
be moved to the next line.
What is token and types?
Token is the basic element or basic unit of java program.
Types:
● Keywords
● Identifiers
● Separators
● Literals
What is keywords?
● Keywords are nothing but predefined words or reserved
words.
● Being a programmer we can't able to change the
meaning of the keyword.
● Keywords should be always return in lowercase.
● In java we are having 49+ keywords
Ex:class,public,static,final,return,abstract......etc
What is identifiers?
● In java we are having components such as
class,methods,variable,interface,package is called as
identifiers.
● For this identifier we the programmers can give the
names to identify it.
What are the rules of compiler for naming the
identifier?
1. We cannot start identifier name with numerical
values.ex:12Demo
2. We can have numerical values in between or last for
identifiers.ex:Demo12
3. Identifiers cannot be keywords.ex:class static
4. Except "$" and "_" no other keywords is used in
identifiers.ex:_Demo$
5. Identifiers cannot have space in between.ex: De mo
What is conventions?
Conventions are nothing but project manager rules
Java naming convention is a rule to follow as you decide what
to name your identifiers such as class, package, variable,
constant, method etc. But, it is not forced to follow. So, it is
known as convention not rule. All the classes, interfaces,
packages, methods and fields of java programming language
are given according to java naming convention.
conventions Single word Multi words
class Test MyTestProgram
methods test() myTestProgram()
variables age my_age
What is separators?
In java we use separators to separate the instructions.
Ex:{,},.,;,[,],(,),
What is literal and types?
Literals are nothing but data or value.
Types:
1. Integer literal
1. Ex:1,2,14
2. decimal literal
1. Ex:1.2,45.9
3. character literal
1. Ex:'A','k','p'--->should be single valued
4. String literal
1. Ex:"java","sql"
5. boolean literal
1. Ex:true,false --->should be written in lower case
What is datatype?
● Datatype is used to create a container.
● Datatype also specifies what type of data is stored
inside the container.
● We are classifying datatypes based on no.of.values that
container can store.
● primitive datatypes
● Non-primitive datatypes
What is primitive datatypes?
A primitive type is predefined by the programmer and is also
called as reserved keyword. Primitive values do not share
state with other primitive values.
The eight primitive data types supported by the Java
programming language are:
Primitive
datatypes
Default
size
Default value Data that can be
stored
byte 1 byte 0 integer
short 2
bytes
0 integer
int 4
bytes
0 integer
long 8
bytes
0 integer
float 4
bytes
0.0f
integer&decimal
double 8
bytes
0.0d
integer&decimal
char 2
bytes
Space('\u0000′)
integer&character
boolean 1 bit false true/false
What is non-primitive datatypes?
These data types are not actually defined by the programming
language but are created by the programmer. They are also
called “reference variables” or “object references” since they
reference a memory location which stores the data.
Ex:string,array,collection,class,interface
What is variable?
It is a named block of memory created by the datatype.
Syntax for declaration:
datatype variable_name;
Ex:int a;
Syntax for initialization:
datatype variable_name=value/expression;
Ex: int a=10;
What kind of variables a class can consist of?
A class consist of Local variable and global variables.
What is a global Variable?
Any variables which is declared outside method and inside the class
is called as Global variables.
What is a local Variable?
Any variables which is declared inside the method and inside the
scope of class is called as local variables.
What is the difference between local variable and
global variable?
Local variable Global variable
Variables which are declared
inside the
method and within the scope of
class.
Variables which are declared
outside
the method and within the scope
of
class.
Local variables are accessible
only
within the method in which they
are
declared, they are not accessible
outside of that method.
Global variables are accessible
everywhere within the scope of a
class.
It is mandatory to initialize local It is not mandatory to initialize, if
we
variables, if we did not initialize
we will
get compile time error.
did not initialize, JVM will take
default
values based on data types.
There are no types for local
variables.
Global variables are divided into
2
types i.e. static and non-static.
Local variables can be default or
final
Global variables can be public,
private,
protected, default or final.
Local variables are present in
Stack
area.
Global variables are present in
Heap Area and also class static
area.
What is operators and its types?
Operator is used to perform some operation with the help of
operands.
Ex: 10+20(+--->operator,10,20--->operands).
Types:
● Unary operator-which accepts only one operand.
● Binary operator-which accepts two operand.
● Ternary operator-which accepts three operand.
Based on these types of operators operator is further classified
into different types.
1. Arithmetic operator.
2. Relational operator.
3. Logical operator.
4. Conditional operator.
5. Increment decrement operator.
6. Typecast operator.
7. Compound assignment operator.
What is concatination?
● If any one operand is String plus operator will always
act as concatination.
Ex: String s="java";
int a=123;
System.out.println(s+a); / / "java"+123--->"java123"
System.out.println("I am "+s+" developer"); / / "I am
java"+"developer"--->I am java developer
● After concatination result will always be string
System.out.println(123+" "); / /"123 "
What is increment decrement operator?
OPERATOR TYPES OPERATION
++ (
INCREMENT )
++ i ( pre
increment )
i ++ ( post
increment )
• Increase the value by 1
and
update
• Substitute the updated
value
• Use the updated value
• Substitute
• Increase the value by 1
and update
• Use the substituted
value
-- (
DECREMENT )
-- i ( pre
decrement )
i -– ( post
decrement )
• decrease the value by
1
and update
• Substitute the updated
value
• Use the updated value
• Substitute
• decrease the value by
1 and update
• Use the substituted
value.
What is conditional operator?
It is a ternary operator.
Syntax to create conditional operator :
(Operand 1) ? Operand 2 : Operand 3
(Condition) ? Statement1 : Statement2
OPERATION :
1) The return type of operand 1 must be Boolean.
2) If the condition is true, Statement1 will get executed else
Statement 2 will get executed.
What is typecasting operator and its types?
The process of converting one datatype into another datatype
is called as typecasting operator.
Types:
● Primitive typecasting.
● Non-primitive typecasting.
What is primitive typecasting and its types?
The process of converting one primitive datatype into another
primitive datatype is called as typecasting operator.
Types:
● Widening-the process of converting lower range into
higher range
Ex:byte-->int
● Narrowing-the process of converting higher range into
lower range
Ex:double-->int
What is method and its syntax?
Method is a block of instruction which is used to perform some
specific task.
Syntax:
[Access modifier][modifier]returntype methodname([formal
args])
What are the types of methods?
● No argument method.
● Parameterized method.
What is no-argument method?
A method which is having zero formal arguments is called as
no-argument method.
Ex:demo()
m1()
What is parameterized method?
A method which is having formal arguments is called as
parameterized method.
Ex:demo(int a)
Public static void demo(int a,double b)
What is access modifier?
● The access modifiers in Java specifies the accessibility
or scope of a field, method, constructor, or class. We
can change the access level of fields, constructors,
methods, and class by applying the access modifier on
it.
● There are four types of Java access modifiers:
1. Private: The access level of a private modifier is only
within the class. It cannot be accessed from outside the
class.
2. Default: The access level of a default modifier is only
within the package. It cannot be accessed from outside
the package. If you do not specify any access level, it
will be the default.
3. Protected: The access level of a protected modifier is
within the package and outside the package through
child class. If you do not make the child class, it cannot
be accessed from outside the package.
4. Public: The access level of a public modifier is
everywhere. It can be accessed from within the class,
outside the class, within the package and outside the
package.
What is modifier?
Modifier is used to modify the characteristics for classes and
methods.
● For classes, you can use either final or abstract:
Modifier Description
final The class cannot be inherited by other
classes,
abstract The class cannot be used to create objects
(To access an abstract class, it must be
inherited from another
class.)
● For attributes and methods, you can use the one of the
following:
Modifiers
Description
final Attributes and methods cannot be
overridden/modified
static Attributes and methods belongs to the class,
rather than an object
abstract Can only be used in an abstract class, and can
only be used on methods. The method does not
have a body, for example abstract void run();.
The body is provided by the subclass.
Why we use methods?
To reuse code: define the code once, and use it many times.
What is return type?
Return type provides what type of data has to be returned back
to the caller.
There are 3 different types for using return type.
● Primitive datatype
● Void
● Non-primitive datatypes
What is return keyword?
When you use primitive datatypes as return type it is mandatory
that you should provide return keyword .
return keyword should be present as the last statement of a
block.
What happens when a method is called?
● The current execution stops and control is transferred from
caller to the called method.
● The execution of the method starts when the task is done
again the control returns to the caller.
● Execution of the caller resumes.
What is object?
● Anything which is having existence in the real world and
having states and behaviour is called as object.
ex:pen,mobile,book....etc
● The states of an object is represented by non-static
variables.
● The behaviours of an object is represented by non-static
methods.
● Before creating a object we should create the blueprint of
an object.
● In java class is acting like a blueprint of an object which
holds the states and behaviours.
● In a class we can have more than one literals.
How will you create the object?
We can create object with help of classname and with the help
of new keyword.
Syntax:
Classname object-reference_variable=new classname();
What is instantiation?
The process of creating an object is called as instantiation.
What is new keyword?
new keyword will create a block of memory inside the heap
area and will create address and that address is referred back
to the object reference variable.
What is constructors and its types?
⮚ Constructor is a special type of method which is having
name similar to the classname.
Ex:
class Book
{
Book()
}
● Constructors don't have any return type.
● Constructors cannot be static.
● If programmer forgets to add a constructor compiler will
add default constructor.
⮚ The constructor is divided into two types:
● No argument constructor(default constructor)
● Parameterized constructor.
What is no-argument constructor?
The constructor which is having zero formal arguments is called
as no-argument constructor.
Ex:Book()
What is parameterized constructor?
The constructor which is having formal arguments is called as
parameterized constructor.
Ex:Book(String name,double price)
What is this keyword?
this keyword refers to the current object in a method or
constructor.
The most common use of the this keyword is to eliminate the
confusion between class attributes and parameters with the
same name.
What is the use of this keyword?
● Invoke current class constructor.
● Invoke current class method.
● Return the current class object.
● Pass an argument in the method call.
● Pass an argument in the constructor call.
What is super keyword?
● The super keyword refers to superclass (parent)
objects.
● It is used to call superclass methods, and to access
the superclass constructor.
● The most common use of the super keyword is to
eliminate the confusion between superclasses and
subclasses that have methods with the same name.
● To understand the super keyword, you should have a
basic understanding of Inheritance and
Polymorphism.
What is constructor chaining?
The process of one constructor calling inside another
constructor is called as constructor chaining.
It is achieved with the help of
● this()
● super()
What is this() statement?
● this() is used to call the constructor of the same
class.
● If a class is having n number of constructor we can
use this()statement n-1 times.
● We have to use this() statement inside the
constructor as the 1st statement.
● We cannot use this() and super()statement together.
What is object oriented principle system?
To deal with objects we must know the principles of oops.
Principles of oops include:
● Encapsulation
● Inheritance
● Polymorphism
● Abstraction
● Interface
What is encapsulation?
The process of binding the states and behaviour of an object
together with the help of class is called as encapsulation.
The main advantage of encapsulation is data hiding.
What is data hiding?
● Restricting the direct access and providing the indirect
access or secured access with the help of helper methods
is called as data hiding.
● We should hide the data members with the help of private
keyword.
● To access the data members we should use the help of
helper methods that is getters and setters method.
What is getter methods and give the characteristics of
the getter method?
getter method is used to get or fetch the data.
Characteristics:
● It should be having access modifier as public and it
should be having return type as same as the data
member which is hidden.
● It is a no-argument method.
● We can make the data only readable with the help of
getter method.
What is setter method and give the characteristics of
the setter method?
Setter method is used to update or modify the data
member.
Characteristics:
● Access modifier of the setter method should be
public.
● It should be having the return type as void.
● It should be a parameterized method.
● If we want to make the data writable we can use
setter method.
● With the help of setter method before modifying the
data member we can have verification and validation.
What is relationship?
The connection between the objects is called as relationship.
Based on type of relationship we classify relationship into two
types:
● Has-a relationship.
● Is-a relationship.
What is has-a relationship?
The connection between two objects were dependencies exist
is called as has-a relationship.
Based on the level of dependencies we classify has-a
relationship into two types:
● Composition.
● Aggregation.
What is composition?
If the dependency between two objects is in such a way where
one object cannot exist without another object is called as
composition.
Ex:car-engine,mobile-battery,human-brain.
How to achieve composition?
We can achieve composition with the help of early instantiation.
What is early instantiation?
The process of creating one object inside another object and
initializing in the same line is called as early instantiation.
What is aggregation?
If the dependency between two objects is in such a way where
one object can exist without another object is called as
aggregation.
Ex:mobile-sim,pen-pen cap,cup-coffee.
How to achieve aggregation?
We can achieve aggregation with the help of lazy instantiation.
What is lazy instantiation?
The process of creating one object inside another object and
initializing it with the help of helper methods is called as lazy
instantiation.
What is is-a relationship?
The connection between two objects which belong to the same
family is called as is-a relationship.
We can achieve is-a relationship with the help of inheritance
technique.
What is inheritance?
The process of acquiring or inheriting the properties of one
object inside another object is called as inheritance.
Note:
● The object or class which provides the properties is
called as superclass or base class or parent class.
● The object or class which accepts the properties is
called as subclass or derived class or child class.
How to achieve inheritance?
We can achieve inheritance by using extends or implements
keyword.
extends keyword:
extends keyword is used for the inheritance between the
class level and interface level.
implements keyword:
implement keyword is used for the inheritance between
the interface and class.
What are the types of inheritance?
Inheritance are of five types
● Single-level inheritance
● Multi-level inheritance
● Multiple inheritance
● Hierarchical inheritance
● Hybrid inheritance
What is single level inheritance?
If a single super class is having single sub class it is called as
single level inheritance.
What is multi-level inheritance?
If a single super class has morethan one sub class in a different
level is called as multi-level inheritance.
What is multiple inheritance?
If a single sub class has more than one super class in a same
level it is called as multiple inheritance.
NOTE :
● Multiple inheritance has a problem known as the
diamond problem.
● Because of the diamond problem, we can’t achieve
multiple inheritance with the help of class.
● In java, we can achieve multiple inheritance with the
help of an interface.
What is hierarchical inheritance?
If a parent (superclass) has more than one child (subclass) at
the same level then it is known as hierarchical inheritance.
What is hybrid inheritance?
The combination of multiple inheritance and hierarchical
inheritance is known as hybrid inheritance.
What is super () statement?
Super() statement is used to call the constructor of parent
class(super class).
What are the rules of super() statement?
● We can use super() statement only if there is is-a
relationship.
● We can use a super() statement only inside the
constructor of sub class.
● It should be the 1st instruction inside a constructor
body.
● If the programmer forgets to add the super()
statement in no argument constructor compiler will
add the super() inside the default no argument
constructor of child class.
● We cannot use this() and super() statement together
in a single constructor.
What is non-primitive typecasting?
● The process of converting one non-primitive datatype
into another non-primitive datatype is called as
non-primitive typecasting.
● In java to achieve non-primtive typecasting is-a
relationship is mandatory.
● Non-primitive typecasting is divided into two types:
● Upcasting
● Downcasting
What is upcasting?
The process of converting the child class reference into a
parent class reference type is known as upcasting.
NOTE :
● The upcasting is implicitly done by the compiler.
● It is also known as auto upcasting.
● Upcasting can also be done explicitly with the help of a
typecast operator.
● Once the reference is upcasted we can’t access the
members of the child.
Why do we need upcasting ?
● It is used to achieve generalization.
● It helps to create a generalized container so that the
reference of any type of child object can be stored.
What is the disadvantage of upcasting?
There is only one disadvantage of upcasting that is, once the
reference is upcasted its child members can’t be used.
NOTE :
In order to overcome this problem, we should go for
downcasting.
What is downcasting?
The process of converting a parent (superclass) reference type
to a child (subclass) reference type is known as downcasting.
NOTE :
● Downcasting is not implicitly done by the compiler.
● It should be done explicitly by the programmer with the
help of a typecast Operator.
Why do we need downcasting?
● If the reference is upcasted, we can’t use the members
of a subclass.
● To use the members of a subclass we need to downcast
the reference to a subclass
what is ClassCastException ?
● It is a RuntimeException.
● It is a problem that occurs during runtime while downcasting.
When and why do we get a ClassCastException?
When we try to convert a reference to a specific type(class),
and the object does’t have an instance of that type then we get
ClassCastException.
EXAMPLE:
Child c = (Child)new Parent(); //ClassCastException
What is polymorphism?
Polymorphism is derived from two different Greek words
‘Poly’ means Numerous,Many
‘Morphs’ means form Which means Numerous form.
Polymorphism is the ability of an object to exhibit more
than one form with the same name.
What are the types of polymorphism you have?
TYPES OF POLYMORPHISM :
In java we have two types of polymorphism,
1. Compile time polymorphism
2. Runtime Polymorphism
What is compile time polymorphism?
● If the binding is achieved at the compile-time and the
same behavior is executed it is known as compile-time
polymorphism.
● It is also said to be static polymorphism.
How compile time polymorphism is achieved?
It is achieved by :
1. Method overloading
2. constructor overloading
3. Variable shadowing
4. Method shadowing
What is method overloading?
If more than one method is created with the same name but
different formal arguments in the same class are known as
method overloading.
What is constructor overloading?
A class having more than one constructor with different formal
arguments is known as constructor overloading.
What is method shadowing?
If a subclass and superclass have the static method with same
signature , it is known as method shadowing.
Which method implementation gets execute in
method shadowing, depend on what ?
In method shadowing binding is done at compile time ,
hence it is compile time polymorphism. The execution of
the method depends on the reference type and does not
depend on the type of object created.
NOTE :
● Return type should be same or it should be co-variant
return type.
● Access modifier should be same or higher visibility than
super class method.
● Method shadowing is applicable only for the static
method.
● It is compile time polymorphism
● Execution of implemented method depends on the
reference type of an object.
What is variable shadowing?
If the superclass and subclass have variables with same name
then it is known as variable shadowing.
Which variable is used, depend on what ?
In variable shadowing binding is done at compile time , hence it
is a compile time polymorphism. Variable used depends on the
reference type and does not depend on the type of object
created.
NOTE :
Is-a relationship is mandatory.
● It is applicable for both static and non static variable.
● It is a compile time polymorphism.
● Variable usage depends on type of reference and does
not depend on type of object created.
What is runtime polymorphism?
● If the binding is achieved at the runtime then it is known
as runtime polymorphism.
● It is also known as dynamic binding.
● It is achieved by method overriding.
What is method overriding?
● If the subclass and superclass have the non static
methods with same signature , it is known as method
overriding.
What are the rule to achieve method overriding ?
● Is-A relationship is mandatory.
● It is applicable only for non static methods.
● The signature of the subclass method and superclass
method should be same.
● The return type of the subclass and superclass method
should be same until 1.4 version but, from 1.5 version
covariant return type in overriding method is acceptable
(subclass return type should be same or child to the
parent class return type.).
Why do we need method overriding ?
Method overriding is used to either modify or provide new
design for an already existing inherited.
What is abstraction and how to achieve abstraction in
java?
It is a design process of hiding the implementation and showing
only the functionality (only declaration ) to the user is known as
abstraction.
How to achieve abstraction in java?
● In java we can achieve abstraction with the help of
abstract classes and interfaces.
● We can provide implementation to the abstract
component with the help of inheritance and method
overriding.
How Abstraction is helpful in java?
Abstraction is one of the main concepts of OOPS(Object-oriented
program). Abstraction is very much useful in Java as it reduces the
complexity and efforts of programming from selecting Data from the
big pool and showing results which is important for the users.
Abstraction only focuses on the object and not on its
implementation. In simple words, Abstraction is a method of hiding
certain details from end-users and only showing essential
information which is necessary for users.
What are the advantages of Abstraction?
The advantages of Abstraction are:
▪ It is helpful in reducing the complexity of data.
▪ It derives the result for a specific class.
▪ It is helpful in hiding unwanted details from users.
▪ The best example of Abstraction is Television. To use the
Television, we do not need to understand how it works
internally.
How Abstraction is achieved in java?
Abstraction can be achieved by declaring a specific keyword abstract.
The keyword abstract is used as a non-access modifier with the class
and method.
Abstraction can be accomplished through the use of abstract classes
or interfaces. Abstraction can be used with methods and classes.
What is abstract class?
Abstraction class means when the word abstract is used with class,
then no one can instantiate that class. The classes and the methods
of implication can be extended.
Important points to remember:
An abstract class is always declared with the keyword 'abstract'.
It can have both abstract, non-abstract methods.
It is non-instantiable.
It must have static and concrete methods.
The sub-class body and the method cannot be changed.
What is abstract methods?
Abstraction with the method means when the word abstract is used
with the method where the overridden is must for the first concrete
class. The implementation of this method is done where there is only
an abstract class and the subclass which is provided that is inherited.
Important points to remember:
It must have a concrete class.
It does not have any implementation with the body.
It is used when the class is abstracted.
The implementation is achieved when the sub-class is inherited.
When to use abstract class in Java?
The abstract class is used when the class is defined by the keyword
'abstract'.
Following are the ways to use the abstract class:
● The class must be written/assigned as an abstract class.
● The hierarchy is maintained by using abstract class.
● In abstract class types of behavior and implementation details
can be known.
When to use the abstract method in Java?
Following are the ways to use the abstract method:
● The abstract method is used when the word 'abstract' is used in
abstract class.
● The abstract method is used when the class is concrete.
● It declares two more sub-classes.
● The classes must be Overridden.
What are the differences between Abstraction and Encapsulation?
Difference
Abstraction Encapsulation
Basic
Abstraction means
hiding details from
the users and
showing only
necessary details to
the users.
Encapsulation means
binding data in a single unit.
Focus
Abstraction solves the
problem at the design
level.
Abstraction only
focuses on the object
and not how it works.
Encapsulation solves the
problem at the
implementation level.
Encapsulation focus on an
binding data in one unit and
implementing its object, its
behavior and properties,
and what it does.
Conclusion Abstraction breaks
the complexity of the
data.
Encapsulation maintains
the flexibility of the data.
What are the difference between Abstraction and Polymorphism?
Difference Abstraction
Polymorphism
Basic Abstraction is a
technique of showing
necessary details.
Polymorphism is a process
for implementing inherited
data.
Focus
Abstraction is based on
design level pattern.
Polymorphism is used
when single or many types
are not defined by name it
represents any type by
using abstract symbols.
There are two types of
Polymorphism:
Compile-time
Polymorphism (or Static
polymorphism) - Example
Method Overloading
Runtime Polymorphism (or
Dynamic polymorphism) -
Example Method
Overriding .
Conclusion
Abstraction can be
implemented , when
the main class is static
or concrete.
Overridden is must.
Polymorphism can be
implemented when data is
static or dynamic.
Can abstract method can be defined inside the non-abstract class?
No. An abstract method cannot be defined inside the non-abstract
class.
Should abstract methods be overridden?
Yes, all the abstract methods in the subclass should be overridden
because the java compiler will not accept and give the compile-time
error.
What is interface?and what is the syntax?
It is a component in java which is used to achieve 100 % abstraction
with
multiple implementation.
Syntax to create an interface:
[Access Modifier] interface InterfaceName
{
// declare members
}
What are the members that can be declared in an interface?
What is the difference between abstract and Interface?
Why do we need an interface ?
● To achieve 100% abstraction.Concrete non static methods are not
allowed.
● To achieve multiple inheritance.
What all the members are not inherited from an interface ?
Only static methods of an interface is not inherited to both class and
Interface.
Explain features of interfaces in java?
1) All the methods defined in interfaces are implicitly abstract even
though abstract modifier is not
declared.
2) All the methods in interface are public whether they are declared
as public or not.
3) variables declared inside interface are by default public, static and
final.
4) Interfaces cannot be instantiated.
5) we cannot declare static methods inside interface.
6) ‘ implements’ keyword is used to implement interface.
7) Unlike class, interface can extend any number of interfaces.
8) We can define a class inside interface and the class acts like inner
class to interface.
9) An interface can extend a class and implement an interface
10) Multiple inheritance in java is achieved through interfaces.
Is it possible to define a class inside an interface?
Yes, we can define a class inside an interface.
What happens if a class has implemented an interface but has not
provided implementation for that method defined in Interface?
The class has to be declared with an abstract modifier. This will be
enforced by the Java compiler.
Why an Interface method cannot be declared as final in Java?Or, Can
a method within an interface be marked as final?
Not possible. Doing so will result the compilation error problem. This
is because a final method cannot be overridden in java. But an
interface method should be implemented by another class.
So, the interface method cannot be declared as final. The modifiers
such as public and abstract are only applicable for method
declaration in an interface.
Why an interface cannot have a constructor?
Inside an interface, a constructor cannot be called using super
keyword with hierarchy.
Why an Interface can extend more than one Interface but a Class
can’t extend more than one Class?
We know that Java doesn’t allow multiple inheritance because a class
extends only one class. But an Interface is a pure abstraction model.
It does not have inheritance hierarchy like classes.Therefore, an
interface allows to extend more than one Interface.
Is it necessary to implement all abstract methods of an interface?
Yes, all the abstract methods defined in interface must be
implemented.
Can we re-assign a value to a variable of interface?
No, variables defined inside the interface are static and final by
default. They are just like constants. We can’t change their value
once they got.
What is a Marker Interface in Java?
An Interface that doesn’t have any data members or methods is
called marker interface in java. For example, Serializable, Cloneable,
Remote, etc.
What is a Nested interface?
An interface declared inside another interface is called nested
interface. By default, it is static in nature. It is also known as static
interface.
Can we reduce the visibility of interface method while overriding?
No, while overriding any interface methods, we must use public only.
This is because all interface methods are public by default. We
cannot reduce the visibility while overriding them.
Can we define an interface inside a method as local member?
No, we can’t define an interface as local member of a method like
local inner class.
What are packages in java?
Package is a mechanism to group related classes ,interfaces and
enums in to a single module.
Package can be declared using the following statement :
Syntax : package <package-name>
Coding Convention : package name should be declared in small
letters.
package statement defines the namespace.
The main use of package is
1) To resolve naming conflicts
2) For visibility control : We can define classes and interfaces that are
not accessible outside the
Class.
Can we have more than one package statement in source file ?
We can’t have more than one package statement in source file. In any
java program there can be atmost
only 1 package statement. We will get compilation error if we have
more than one package statement in
source file.
Can we define package statement after import statement in java?
We can’t define package statement after import statement in java.
package statement must be the first
statement in source file. We can have comments before the package
statement.
What is array?
Array is a linear data Structure.It is a continuous block of memory
which is used to store the group of objects.
Characteristics of array:
The size of an array must be defined at the time of declaration.
Once declared , the size of an array can’t modified.
Hence array is known as fixed in size.
In an array we can access the elements with the help of an index or
subscript. It
is an integer number that starts from 0 and ends at length of the
array-1.
In an array we can store only homogeneous type value. It is also
known as
homogeneous collection of an object.
Can we call the main() method of a class from another class?
Yes! We can call the main() method of a class from another class
using Classname.main(). At the time of calling the main() method, we
should pass a string type array to it.
Is it possible to declare array size as negative?
No, it is not possible to declare array size as negative. Still, if we
declare the negative size, there will be no compile-time error. But we
get the NegativeArraySizeException at run-time.
What is the difference between int array[] and int[] array?
There is no difference between array[] and []array. Both array[] and
[]array are the ways to declare an array. The only difference between
them is that if we are declaring more than one array in a line, we
should use prefix []. If we are declaring a single array in a line, we
should use postfix [].
For example, consider the following declaration:
int array1[], array2; //array1[] is an array while array2 is just a
variable of type int
int[] arr1, arr2; //both arr1 and arr2 are arrays of int type
When ArrayIndexOutOfBoundsException occurs?
The ArrayIndexOutOfBoundsException occurs when the program
tries to access the index of an array. The exception also occurs when
the index is higher than the size of the array or the index is negative.
What is the difference between Array and ArrayList?
Array: Array is static. It is of fixed size. Its size cannot be changed
once it is declared. It contains both primitive data types and objects
of a class. Array does not have generic features.
ArrayList: ArrayList is dynamic in size. Its size or capacity
automatically grows when we add element into it. It contains only
the object entries. It has a generic feature.
How can we check an array contains values or not?
Java Arrays class provides two methods isExists() and contains() to
check an array has elements or not. Both the methods return true if
an array has elements else returns false.
What is string ?
String is a literal or data.
Anything which is enclosed within the" " is called as string literal.
String is a non primitive datatype.
A group of characters which is enclosed within " " is represented as
string.
Is String a keyword in Java?
No. String is not a keyword in Java. String is a final class in java.lang
package which is used to represent the set of characters in Java.
What is string class?
String class is a final class which is present in java.lang package.
We can able to store string data by creating object for three
classes,String class,StringBuffer class,StringBuilder class.
We can able to create object in 2 ways in string class.
1.string literal
2.with the help of new keyword.
Whenever we create object by using string literal object is created
inside heap area in string constant pool.
What is the characteristics of string literal?
Whenever we create object object is created inside the string
constant pool.
If we create onemore object before creating the object string literal
check whether the object is already present in string constant pool if
it is present it will not create new object instead it refer back the
reference of the object.
What is the disadvantage of string class?
Disadvantage of string class is immutable.
Immutable means once object is created we can't able to modify the
object if we try to modify one more new object will be created.
To overcome this process we will go for StringBuffer and
StringBuilder.
What is string constant pool?
String objects are most used data objects in Java. Hence, Java has a
special arrangement to store the string objects. String Constant Pool
is one such arrangement. String Constant Pool is the memory space
in the heap memory specially allocated to store the string objects
created using string literals. In String Constant Pool, there will be no
two string objects having the same content.
Whenever you create a string object using string literal, JVM first
checks the content of the object to be created. If there exist an
object in the string constant pool with the same content, then it
returns the reference of that object. It doesn’t create a new object. If
the content is different from the existing objects then only it creates
new object.
What do you mean by mutable and immutable objects?
Immutable objects are like constants. You can’t modify them once
they are created. They are final in nature. Where as mutable objects
are concerned, you can perform modifications on them.
What is StringBuffer?
StringBuffer is a class which is present in java.lang package.
It is a final class.
It creates a mutable string object.
In StringBuffer we don't have the concept of String constant
pool.hence,object is created in heap area.
It inherits object class.
Only toString() is overridden and equals() and hashcode() is not
overridden.
Why StringBuffer and StringBuilder classes are introduced in Java
when there already exist String class to represent the set of
characters?
The objects of String class are immutable in nature. i.e you can’t
modify them once they are created. If you try to modify them, a new
object will be created with modified content. This may cause
memory and performance issues if you are performing lots of string
modifications in your code. To overcome these issues, StingBuffer
and StringBuilder classes are introduced in Java.
What is the disadvantage of StringBuffer?
Multiple thread can’t execute the StringBuffer object simultaneously
because all the methods are synchronized. So, Execution time is
more. In order to overcome this problem we will go for String Builder.
In Java, how can two strings be compared?
In Java, there are several ways for comparing two strings.
equals(): In this method, the strings are compared based on the
values within them. If the values of the two strings are the same, it
returns true; otherwise, it returns false. This method is
case-sensitive.
Syntax:str1.equals(str2);
equalsIgnoreCase() :By using this method, the two strings are
compared without taking into account the case (upper or lower). It
returns true if the two values are the same and not null.
Syntax:str1.equalsIgnoreCase(str2);
ObjectEquals(): The method returns true if its arguments are equal,
otherwise, it returns false. Accordingly, if both arguments are null,
the result is true, and if just one argument is null, the result is false.
Syntax:Object.equals(str1, str2);
CompareTo(): This method compares input strings with each other.
Upon comparison, the following value is returned:
If (str1>str2), a positive value is returned.
If (str1==str2), 0 is returned.
If (str1<str2), a negative value is returned.
Syntax:str1.compareTo(str2);
What is the difference between str1 == str2 and str1.equals(str2)?
Java offers both the equals() method and the "==" operator for
comparing objects. However, here are some differences between the
two:
Essentially, equals() is a method, while == is an operator.
The == operator can be used for comparing references (addresses)
and the .equals() method can be used to compare content. To put it
simply, == checks if the objects point to the same memory location,
whereas .equals() compares the values of the objects.
What is the difference between StringBuffer and StringBuilder?
STRING BUFFER STRING BUILDER
All the method present
in StringBuffer is
synchronized.
All the method present
in StringBuilder is non
synchronized.
At a time only one
thread is allowed to
access String Buffer
object.
Hence it is Thread safe.
At a time multiple
thread is allowed to
access String Builder
object.
Hence it is Not Thread
safe.
Threads are required to
wait to operate a
stringBuffer object.
Hence Relatively
performance is low .
Threads are not
required to wait to
operate a StringBuilder
object.
Hence Relatively
performance is high.
Less efficient than
StringBuilder
Efficiency is high
compared to
StringBuffer
Introduced in 1.0 v Introduced in 1.5v
What is an exception?
Exception is an abnormal condition which occurs during the
execution of a program and disrupts normal flow of a program. This
exception must be handled properly. If it is not handled, program will
be terminated abruptly.
What are the types of exception?
1.checked Exception.
2.Unchecked Exception.
what are checked and unchecked exceptions in java?
Checked exceptions are the exceptions which are known to compiler.
These exceptions are checked at compile time only. Hence the name
checked exceptions. These exceptions are also called compile time
exceptions. Because, these exceptions will be known during compile
time itself.
Unchecked exceptions are those exceptions which are not at all
known to compiler. These exceptions occur only at run time. These
exceptions are also called as run time exceptions. All sub classes of
java.lang.RunTimeException and java.lang.Error are unchecked
exceptions.
How the exceptions are handled in Java? OR Explain exception
handling mechanism in Java?
Exceptions in Java are handled using try, catch and finally blocks.
try block : The code or set of statements which are to be monitored
for exception are kept in this block.
catch block : This block catches the exceptions occurred in the try
block.
finally block : This block is always executed whether exception is
occurred in the try block or not and occurred exception is caught in
the catch block or not.
What is try block?
Java try block is used to enclose the code that might throw an
exception. It must be used within
the method.
If an exception occurs at the particular statement of try block, the
rest of the block code will not
execute. So, it is recommended not to keeping the code in try block
that will not throw an
exception.
Java try block must be followed by either catch or finally block.
What is catch block?
Java catch block is used to handle the Exception by declaring the type
of exception within the
parameter. The declared exception must be the parent class
exception ( i.e., Exception) or the
generated exception type. However, the good approach is to declare
the generated type of
exception.
The catch block must be used after the try block only. You can use
multiple catch block with a
single try block.
Syntax of Java try-catch
try{
//code that may throw an exception
}catch(Exception_className ref){
}
Syntax of try-finally block
try{
//code that may throw an exception
}finally{
}
Can we able to use multiple catch block?
A try block can be followed by one or more catch blocks. Each catch
block must contain a different
exception handler. So, if you have to perform different tasks at the
occurrence of different
exceptions, use java multi-catch block.
A Single try block can have multiple catch blocks but only one finally
block.
Try , catch and finally block must always be associated together.
There must not be any executable
code between them.
try {
}
catch() {
}
catch() {
}
try {
}
catch() {
}
catch() {
}
finally {
}
How catch block gets executed?
Catch block gets executed only if there are any exception in try block.
❖ At any given point of time only one exception can occur in try
block , multiple exception
cannot occur at same time.
❖ Once an exception occurs in the try block , the control
immediately comes out of try
block and without executing the remaining code within try block.
❖ When control comes out of try block then if matching catch block
is found , it gets
executed , if not program gets terminated.
❖ At any given point of time for a single exception only one catch
block gets executed.
❖ Once control comes out of try block then it will not go back to try
block again.
❖ Catch block gets executed only if there some error in try block.
What is the difference between error and exception in Java?
Errors are mainly caused by the environment in which an application
is running. For example, OutOfMemoryError happens when JVM runs
out of memory. Where as exceptions are mainly caused by the
application itself. For example, NullPointerException occurs when an
application tries to access null object.
Can we write only try block without catch and finally blocks?
No, it shows compilation error. The try block must be followed by
either catch block or finally block.
What are run time exceptions in Java. Give example?
The exceptions which occur at run time are called as run time
exceptions. These exceptions are unknown to compiler. All sub
classes of java.lang.RunTimeException and java.lang.Error are run
time exceptions. These exceptions are unchecked type of exceptions.
For example, NumberFormatException, NullPointerException,
ClassCastException, ArrayIndexOutOfBoundException,
StackOverflowError etc.
Can we keep the statements after finally block If the finally block is
returning the control?
No, it gives unreachable code error. Because, control is returning
from the finally block itself. Compiler will not see the statements
after it. That’s why it shows unreachable code error.
Does finally block get executed If either try or catch blocks are
returning the control?
Yes, finally block will be always executed no matter whether try or
catch blocks are returning the control or not.
What is throw keyword?
The Java throw keyword is used to explicitly throw an exception. We
can throw either checked or uncheked exception in java by throw
keyword. The throw keyword is mainly used to throw custom
exception.
The syntax of java throw keyword is :
throw exception;
throw new IOException("sorry device error");
Can we write any code after throw statement?
After throw statement jvm stop execution and subsequent
statements are not executed. If we try to write
any statement after throw we do get compile time error saying
unreachable code.
What is throws keyword?
❖ throws is a keyword which is used with method declaration , it is
used to indicate the
possibility of exception from a method.
❖ throws keyword does not throw an exception rather it only
indicates the possibility of
exception.
❖ Using throws we can indicate multiple exceptions.
❖ When we call a method which has throws declaration , then we
have to handle the code by
using try and catch block.
What is customException?
Being a programmer if we create our own exception it is called as
customException.
There are 2 important methods which are useful for debugging the
exception.
public void printStackTrace()
public String getMessage()
both the methods are defined in super most class called Throwable.
Hence it is inherited to all the classes which inherit or extends
Throwable.
When an inbuilt exceptions are not enough then its possible to write
or define our own exceptions.
Writing custom exception is a 2 step process.
1. Write a class which extends either Throwable or Exception or
RuntimeException class.
2. Override toString() method and getMessage() method.
What is finally block?
It is a block which is used in exception handling .
Finally block always gets executed irrespective of whether exception
occurs or not.
A single try block can have maximum of one finally block.
Explain importance of finally block in java?
Finally block is used for cleaning up of resources such as closing
connections, sockets etc. if try block
executes with no exceptions then finally is called after try block
without executing catch block. If there is
exception thrown in try block finally block executes immediately after
catch block.
If an exception is thrown,finally block will be executed even if the no
catch block handles the exception.
Explain the importance of finally over return statement?
finally block is more important than return statement when both are
present in a program. For example if
there is any return statement present inside try or catch block , and
finally block is also present first
finally statement will be executed and then return statement will be
considered.
Explain a situation where finally block will not be executed?
Finally block will not be executed whenever jvm shutdowns. If we use
system.exit(0) in try statement
finally block if present will not be executed.
Can we have any code between try and catch blocks?
We shouldn’t declare any code between try and catch block. Catch
block should immediately start after try
block.
try{
//code
}
System.out.println(“one line of code”); // illegal
catch(Exception e){
//
}
Can we have any code between try and finally blocks?
We shouldn’t declare any code between try and finally block. finally
block should immediately start after
catch block.If there is no catch block it should immediately start after
try block.
try{
//code
}
System.out.println(“one line of code”); // illegal
finally{
//
}
Can we catch more than one exception in single catch block?
From Java 7, we can catch more than one exception with single catch
block. This type of handling reduces
the code duplication.
Note : When we catch more than one exception in single catch block ,
catch parameter is implicity final.
We cannot assign any value to catch parameter.
Ex : catch(ArrayIndexOutOfBoundsException || ArithmeticException
e)
{
}
In the above example e is final we cannot assign any value or modify
e in catch statement.
List out five keywords related to Exception handling ?
1) Try
2) Catch
3) throw
4) throws
5) finally
Explain the importance of throwable class and its methods?
Throwable class is the root class for Exceptions. All exceptions are
derived from this throwable class. The
two main subclasses of Throwable are Exception and Error. The three
methods defined in throwable class
are :
1) void printStackTrace() :
This prints the exception information in the following format :
Name of the exception, description followed by stack trace.
2) getMessage()
This method prints only the description of Exception.
3) toString():
It prints the name and description of Exception.
What is wrapper class?
The wrapper class in java provides mechanism to wrap the primitive
into
an object.
For every primitive data type corresponding class is declared known
as a
wrapper class.
There are eight wrapper classes declared in java.lang package which
provides several methods to convert primitive into an object.
Explain different types of wrapper classes in java?
For every primitive in java we have corresponding wrapper class.
Here are list of wrapper classes
available in java.
What is boxing?
The process of converting a primitive datatype into non primitive
datatype is called as boxing.
Ex:
class Demo{
public static void main(String[] args){
int i=100;
Integer a=i;
System.out.println(a);//100 ----> Integer type
System.out.println(i);//100----->int type
}
}
What is autoboxing?
It is the process of implicit conversion of primitive data type into its
corresponding non primitive
wrapper type. for example, byte to Byte, char to Character,….we can
convert it with the help of valueOf();
Ex:class Demo{
public static void main(String[] args){
byte b = 10;
short s = 20;
Byte obj1 = Byte.valueOf(b);
Short obj2 = Short.valueOf((s);
System.out.println(obj1);
System.out.println(obj2);
}
}
What is unboxing?
The process of converting non primitive datatype into primitive
datatype is called as unboxing.
Ex:Integer-int,Boolean-boolean….
class Demo{
public static void main(String[] args){
Double d=123.9;
double d1=d;
System.out.println(d1);
}
}
What is autounboxing?
It is the process of implicit conversion of object(NPDT)into primitive
datatype is known as autounboxing.
Ex:Integer-int,Boolean-boolean..we can convert it with the help of
value();
Class Demo{
public static void main(String[] args){
Long i = 20l;
long l = i.longValue();
System.out.println(i);//20--->Long type
System.out.println(l);//20--->long type
}
}
What is parsing?
The process of converting string into primitive datatype except the
character is called as parsing.
Note:
The runtime string should be of number format, otherwise we will
get NumberFormatException during runtime.
What data should be used while we use parseBoolean() as a string?
If we pass data in string while converting string to primitive type if
string contains boolean data it will return true else return false.
What is collection ?
A collection is a container which holds group of objects. Collection
provides a way to manage objects
easily. Collections manages group of objects as single unit.
Examples include list of strings, integers etc.
Here are few basic operations we do on collections :
1) Adding objects to collection.
2) Removing or deleting objects from collection.
3) Retrieving object from collection.
4) Iterating collection.
What is framework in Java?
A framework is a popular and readymade architecture that contains a
set of classes and interfaces.
What is the Collection framework in Java?
Collection Framework is a grouping of classes and interfaces that is
used to store and manage the objects. It provides various classes like
Vector, ArrayList, HashSet, Stack, etc. Java Collection framework can
also be used for interfaces like Queue, Set, List, etc.
Difference between collection, Collection and Collections in java?
collection : represent group of objects where objects are stored.
Collection : This is one of the core interface which provides basic
functionality for collection.
Collections : Collections contains some utility static methods that
operate on collections.
Why we need to go for collection framework?
To store multiple objects we have array but array has some
limitations,that’s why we use collection framework.
Limitations of array:
Once array size is fixed we can’t able to modify the size of the array.
Array is homogeneous collection of elements.
Array manipulation such as :
• Removing an element from an array
• Adding an element in between the array etc..
Requires complex logics to solve.
Therefore, to avoid the limitations of the array we can store the
group of objects or elements using different data structures,
such as:
1) List
2) Set
3) Queue
4) Maps / dictionaries
What is collection interface?
1)Collection is an interface defined in java.util package.
2) Collection interface provides the mechanism to store group of
elements ( objects) together.
3) All the elements in the collection are stored in the form of Objects
( i.e only non primitive data types are
allowed)
4)Collection interface provides the abstract methods to the
programmer to perform the following task.
a. Add an element into the collection
b. Search an element in the collection
c. Remove an element in the collection
d. Access/ read the elements present in the collection.
What is list interface and its characteristics?
1. List interface is defined in java.util package
2. List is a sub interface of collection interface.
3. Therefore it has all the methods inherited from collection
interface.
Characteristics of List interface:
1. List is a collection of objects.
2. List maintains the insertion order of elements. The element
inserted first, it will be maintained in the 1st position.
3. It allows duplicate entries. We can add same object (element)
multiple times.
4. List supports indexing. We can insert , search , remove, access
elements with the help of index.
5. The index starts from zero up to (list size-1)
6. List interface will have all the inherited abstract methods from
iterable and collection interfaces.
What is ArrayList in java?
It is a concrete implementing class of list interface.
ArrayList is a data structure that can be stretched to accommodate
additional elements within itself and shrink back to a smaller size
when elements are removed. It is a very important data structure
useful in handling the dynamic behavior of elements.
All the abstract methods of List and Collection interface is
implemented.
2) We can create an object ( instance) ArrayList.
Difference between Array and ArrayList ?
Arrays are used to store primitives or objects of same type or
variables that are subclasses of same type.
ArrayList : It is an ordered collection which grows dynamically.
In list we can insert nulls values and list allows duplicate elements
ARRAY ARRAYLIST
While creating array we have to
know the
size.
But it is not required to know size
while
creating ArrayList, because arraylist
grows
dynamically.
To put an element in to array we
use the
following syntax :String array[] =
newString[5];array[1] = “java”;We
must know
specific location to insert an
element in to
array. If we try to put element in
index which is
out of range we get
ArrayIndexOutOfBounds
Exception
We can add element to arraylist by
following
syntax :List<String> l = new
ArrayList<String>();
l.add(“java”);
Arrays are static ArrayList is dynamic
We can store objects and
primitives.
We can store only primitives prior
to 1.5 . From 1.5 we can store even
objects also.
We have to manually write logic
for inserting
and removing elements.
Just a method call would add or
remove
elements from list.
Arrays are faster ArrayList is slower
What is vector?
Vector is similar to arraylist used for random access.
Vector is a dynamic array like arraylist.
vector size increases or decreases when elements are added and
removed .
Vector is synchronized .
vector and Hashtable are the only collections since 1.0.
Rest of the collections are added from 2.0.
public class Vector<E>extends AbstractList<E>implements List<E>,
RandomAccess, Cloneable, java.io.Serializable
Difference between arraylist and vector ?
Both ArrayList and vector grows dynamically. The differences
between arraylist and vector are :
1) Arraylist is not synchronized and vector is synchronized.
2) Vector is legacy collection introduced in 1.0 and Arraylist
introduced in java 2.0.
Performance wise it is recommended to use arraylist rather than
vector because by default vector is
synchronized which reduces performance if only one thread accesses
it.
What is Comparable Interface?
It is used to sort collections and arrays of objects using the
collections. sort
and java.util. The objects of the class implementing the Comparable
interface can
be ordered.
Define Linked List and its features with signature ?
Linked list is used for storing a collection of objects that allows
efficient addition and removal of elements
in the middle of the collection.
The main drawback with arrays is if we want to insert an element in
the middle of the list we need to
move each element to next position and insert the element. Similarly
with remove if we want to remove
an element we need to remove the element and move the list of
elements.
But with linked list we can insert and delete in the middle of the list
efficiently by just updating the
neighbouring node reference.
Linked list class is in java.util package.
Linked List class extends class extends AbstractSequentialList and I
mplements List, Deque, Cloneable
and Serializable.
Signature :public class LinkedList<E> extends
AbstractSequentialList<E>
implements List<E>, Deque<E>, Cloneable, java.io.Serializable
{
}
Important methods specific to LinkedList class :
1) public E getFirst() :
getFirst() will returns the first element in the list.
2) public E getLast() :
getLast() returns the last element in the list.
3) public E removeFirst() :
removeFirst() method removes the first element in the list.
4) public E removeLast() :
removeLast() method removes the last element in the list.
5) public void addFirst(E e)
Inserts the element at beginning of the list.
6) public void addLast(E e) :
Inserts the element at end of the list
Difference between comparator and comparable?
Comparable Comparator
Comparable provides
compareTo() method to sort
elements in Java.
Comparator provides compare()
method to sort elements in Java.
Comparable interface is present
in java.lang package.
Comparator interface is present in
java. util package.
The logic of sorting must be in
the same class whose object you
are going to sort.
The logic of sorting should be in a
separate class to write different
sorting based on different attributes
of objects.
The class whose objects you
want to sort must implement
the comparable interface.
Class, whose objects you want to
sort, do not need to implement a
comparator interface.
It provides single sorting
sequences.
It provides multiple sorting
sequences.
This method can sort the data
according to the natural sorting
order.
This method sorts the data
according to the customized sorting
order.
It affects the original class. i.e.,
the actual class is altered.
It doesn’t affect the original class,
i.e., the actual class is not altered.
Implemented frequently in the
API by Calendar, Wrapper
classes, Date, and String.
It is implemented to sort instances of
third-party classes.
All wrapper classes and String
class implement the comparable
interface.
The only implemented classes of
Com
What are all the ways to access arraylist element?
1. get method
2. Iterator
3. ListIterator
4. For each loop.
What is iterator()?
● iterator() is a method which belongs to Iterable interface.
● iterator() method creates an Iterator type object and returns
the reference.
● iterator() method returns the reference in Iterator (interface)
type.
What are the methods present in iterator()?
hasNext() : it checks whether there is an element to be accessed
from the collection, if present it returns true else it returns false.
next() : it is used to access the element, and moves the cursor to the
next element. The return type Of next() is Object.
Here we will get one exception called as NoSuchElementException.
What is NoSuchElementException?
when we try to access an element using next() method and if there is
no element Present, we get NoSuchElementException.
What is the disadvantage of iterator()?
1) We can iterate only once.
2) We cannot access the elements in reverse order.
3) We cannot add or remove an element from the collection, during
iteration. We get an exception called as
(ConcurrentModificationException).
What is listIterator?
ListIterator is a sub interface (child ) of Iterator interface, it is defined
in java.util package
Methods present in listiterator:
hasNext() To check whether next element to be accessed
is present or not
And return boolean value.
Next() It gives the element, and moves the cursor
forward.
hasPrevious() To check whether previous element to be
accessed is present or not.
previous() It gives the previous element pointed by the
cursor, and moves the cursor backward.
remove(Object) It removes the current object pointed, from the
collection, which is under iteration.
Add(object) It is used to add a new object into the
collection.
listIterator() method is overloaded :
1) listIterator() : creates an ListIterator object type, and cursor will be
pointing to first element.
2) listIterator(int index) : creates an ListIterator object type, and
cursor will be pointing to the position provided.
What are the types of collection we have?
There are two types of collection
1.generic collection
2.non-generic collection.
What is non-generic collection?
It is a heterogeneous( different type) collection of elements.
Every element getting stored, is converted to java.lang.Object type.
What is generic-collection?
It is a homogeneous (same type) collection of elements.
Syntax to create generic collection:
Syntax to create reference variable for generic collection:
Collection_type < Non-primitive datatype> variable ;
ArrayList <Integer> al ;
Syntax to create generic collection object:
new collection_name < data_type> () ;
new ArrayList < Integer> () ;
In this ArrayList we can store only Integer.
2.From jdk 7 onwards,
ArrayList <Integer> al = new ArrayList < > () ;
Note:
1) The elements are not converted to java.lang.Object type, instead
they are stored or converted
To its respective generic type
2) The return type of the elements in generic collection will be same
as the given generic type.
What are the advantages of Array List over arrays?
Array List can grow dynamically and provides more powerful
insertion and
search mechanisms than arrays.
Why deletion in Linked List is fast than Array List?
Deletion in linked list is fast because it involves only updating the
next
pointer in the node before the deleted node and updating the
previous pointer in the
node after the deleted node.
How do you decide when to use Array List and Linked List?
If you need to frequently add and remove elements from the middle
of the
list and only access the list elements sequentially, then LinkedList
should be used.
If you need to support random access, without inserting or removing
elements from
any place other than the end, then Array List should be used.
Why Vector class is used?
The Vector class provides the capability to implement a growable
array of
objects. Vector proves to be very useful if you don't know the size of
the array in
advance, or you just need one that can change sizes over the lifetime
of a program.
What is comparable?
1) Comparable is an interface defined in java.lang package
2) Comparable interface has one abstract method
abstract public int compareTo(Object o) ;
Steps to make a class comparable type:
• The must implement Comparable interface
• It should override compareTo(Object o) method
Design tip of overriding compareTo(Object) :
It is used to compare the attribute of current object with the
attribute of the passed object
Note:
Case1: it should return 0 :
If both the attributes are same
Case2: it should return +ve integer:
If the value of the current object is greater than the passed object.
Case3: it should return -ve integer:
If the value of the current object is less than the passed object.
What is set?
1) It is a sub interface of Collection, therefore all the methods of
Collection is inherited
2) Set is defined in java.util package
Characteristics of Set:
1) It is an unordered collection of elements. ( the order of
insertion in not followed).
2) Set does not allow duplicate elements
3) Set does not have indexing. Therefore, we cannot access, insert or
remove elements based on index.
We can access the elements of Set by using:
1) Iterator()
2) for each
What is HashSet?
• It is a concrete implementing class of Set interface.
• It has all the methods inherited from Collection interface.
Characteristics:
1. It is unordered
2. No Duplicates
3. No index
What is TreeSet?
1) TreeSet is a concrete implementing class for Set interface
2) TreeSet has all the methods of Collection interface
Characteristics of TreeSet:
1. The elements will be in sorted order by default.
2. The elements to be added in the TreeSet must be comparable
type, else we get ClassCastException
3. All the elements in TreeSet should be of same type
(Homogeneous), if not we get ClassCastException
4. Duplicates are not allowed
5. No indexing , therefore adding and removing the elements is not
possible with index.
What is Map?
Map is a data structure, which helps the programmers to store the
data in the form of key value pairs.
Where every value is associated with a unique key.
NOTE :
● Key can’t duplicate.
● One key can be associated with one value.
● Maps helps us to access the value easily with the help of its
associated key.
What is MapInterface?
1. Map is an interface in java defined in java.util package.
2. We can create generic map by providing the type for both key
as well as value, <key_type, value_type>,<K,V>
Ø We can obtain three different views of a map.
1. We can obtain a list of values from a map.
2. We can obtain a set of keys from a map.
3. We can obtain a set of key-value pairs.
What is a Values Collection View ?
It is a collection returned by the values method of the Map Interface,
It contains all the objects present as values in the map.
What is HashMap and what are the characteristics?
It is a concrete implementing class of Map interface, which is used to
store multiple objects in the form of key value pairs.
Characteristics of HashMap :
The order of insertion is not maintained.
Key can’t be duplicate but value can be duplicate.
One key can be null.
Multiple values can be null.
What is TreeMap and what are the characteristics?
It is a concrete implementing class of Map interface which is used to
store multiple objects in the key-value pair.
Characteristics of TreeMap :
● Internally it uses Tree data structure to store the data.
● It will sort the entries in the Map with respect to keys in the
defined natural ordering.Therfore,the keys must be comparable type
else we getClassCastException.
● We can’t have null as a key but a value can be null.
What is LinkedHashMap and what are the characteristics?
A LinkedHashMap contains values based on the key. It implements
the Map interface and extends the HashMap class. It contains only
unique elements. It may have one null key and multiple null values.
Characteristics :
Everything is same as HashMap the only difference is the order of
insertion is maintained.
What is Hashtable and what is the charateristics of hashtable?
A Hashtable is an array of a list. Each list is known as a bucket. The
position of the bucket is identified by calling the hashcode() method.
A Hashtable contains values based on the key.
Java Hashtable class contains unique elements.
Java Hashtable class doesn't allow null key or value.
Characteristics :
It doesn’t maintain insertion order.
HashTable doesn’t allow null either as a key or a value.
ADDITIONAL QUESTIONS
What is the difference between object oriented programming
language and object based programming language?
Object based programming languages follow all the features of OOPs
except Inheritance. JavaScript is an example of object based
programming languages.
What is the difference between a break statement and a continue
statement?
A break statement results in the termination of the statement to
which it applies switch ,for ,do ,or while. A continue statement is
used to end the current loop iteration and return control to the loop
statement.
What will happen if static modifier is removed from the signature of
the main method?
Program throws "No Such Method Error" error at runtime.
what are static blocks and static initalizers in Java ?
Static blocks or static initializers are used to initalize static fields in
java. we declare static blocks when we want to intialize static fields in
our class. Static blocks gets executed exactly once when the class is
loaded.Static blocks are executed even before the constructors are
executed.
Why main() method is public, static and void in java ?
public : “public” is an access specifier which can be used outside the
class. When main method is declared
public it means it can be used outside class.
static : To call a method we require object. Sometimes it may be
required to call a method without the
help of object. Then we declare that method as static. JVM calls the
main() method without creating
object by declaring keyword static.
void : void return type is used when a method does’nt return any
value . main() method does’nt return
any value, so main() is declared as void.
Signature : public static void main(String[] args) {}
Explain about main() method in java ?
Main() method is starting point of execution for all java applications.
public static void main(String[] args) {}
String args[] are array of string objects we need to pass from
command line arguments.
Every Java application must have atleast one main method.
What is difference between length and length() method in java ?
length() : In String class we have length() method which is used to
return the number of characters in string.
Ex : String str = “Hello World”;
System.out.println(str.length());
Str.length() will return 11 characters including space.
length : we have length instance variable in arrays which will return
the number of values or objects in array.
For example :
String days[]={” Sun”,”Mon”,”wed”,”thu”,”fri”,”sat”};
Will return 6 since the number of values in days array is 6.
What is ASCII Code?
ASCII stands for American Standard code for Information
Interchange. ASCII character range is 0 to 255.
We can’t add more characters to the ASCII Character set. ASCII
character set supports only English. That is the reason, if we see C
language we can write c language only in English we can’t write in
other
languages because it uses ASCII code.
What is Unicode ?
Unicode is a character set developed by Unicode Consortium. To
support all languages in the world Java
supports Unicode values. Unicode characters were represented by 16
bits and its character range is 0-65,535.Java uses ASCII code for all
input elements except for Strings,identifiers, and comments. If we
want to
use telugu we can use telugu characters for identifiers.We can enter
comments in telugu.
Difference between Character Constant and String Constant in java ?
Character constant is enclosed in single quotes(Ex :’2’, ‘A’) .String
constants are enclosed in double quotes
(Ex : “Hello World”)Character constants are single digit or character.
String Constants are collection of characters.
What are constants and how to create constants in java?
Constants are fixed values whose values cannot be changed during
the execution of program. We create
constants in java using final keyword.
Ex : final int number =10;
final String str=”java-interview –questions”.
Can we have multiple classes in single file ?
Yes we can have multiple classes in single file but it people rarely do
that and not recommended. We can
have multiple classes in File but only one class can be made public. If
we try to make two classes in File
public we get following compilation error.
“The public type must be defined in its own file”.
What access modifiers can be used for class ?
We can use only two access modifiers for class public and default.
public: A class with public modifier can be visible
1) In the same class.
2) In the same package subclass.
3) In the same package nonsubclass.
4) In the different package subclass.
5) In the different package non subclass.
default : A class with default modifier can be accesed
1) In the same class.
2) In the same package subclass.
3) In the same package nonsubclass.
4) In the different package subclass.
5) In the different package non subclass.
Explain what access modifiers can be used for methods?
We can use all access modifiers public, private,protected and default
for methods.
public : When a method is declared as public it can be accessed
1) In the same class
2)In the same package subclass
3) In the same package nonsubclass
4)In the different package subclass
5) In the different package non subclass.
default : When a method is declared as default, we can access that
method in
1) In the same class
2) In the same package subclass
3) In the same package non subclass
We cannot access default access method in
1) Different package subclass
2) Different package non subclass.
protected : When a method is declared as protected it can be
accessed
1) With in the same class
2) With in the same package subclass
3) With in the same package non subclass
4) With in different package subclass
It cannot be accessed non subclass in different package.
private : When a method is declared as private it can be accessed
only in that class.
It cannot be accessed in
1) Same package subclass
2) Same package non subclass
3) Different package subclass
4) Different package non subclass.
Explain what access modifiers can be used for variables?
We can use all access modifiers public, private,protected and default
for variables.
public : When a variables is declared as public it can be accessed
1) In the same class
2) In the same package subclass
3) In the same package nonsubclass
4) In the different package subclass
5) In the different package non subclass.
default : When a variables is declared as default, we can access that
method in
1) In the same class
2) In the same package subclass
3) In the same package non subclass
We cannot access default access variables in
4) Different package subclass
5) Different package non subclass.
protected : When a variables is declared as protected it can be
accessed
1) With in the same class
2) With in the same package subclass
3) With in the same package non subclass
4) With in different package subclass
It cannot be accessed non subclass in different package.
private : When a variables is declared as private it can be accessed
only in that class.
It cannot be accessed in
1) Same package subclass
2) Same package non subclass
3) Different package subclass
4) Different package non subclass.
What is final access modifier in java?
final access modifier can be used for class, method and variables. The
main advantage of final access
modifier is security no one can modify our classes, variables and
methods. The main disadvantage of final
access modifier is we cannot implement oops concepts in java. Ex :
Inheritance, polymorphism.
final class : A final class cannot be extended or subclassed. We ar e
preventing inheritance by marking a
class as final. But we can still access the methods of this class by
composition. Ex: String class
final methods: Method overriding is one of the important features in
java. But there are situations where
we may not want to use this feature. Then we declared method as
final which will print overriding. To
allow a method from being overridden we use final access modifier
for methods.
final variables : If a variable is declared as final ,it behaves like a
constant . We cannot modify the value
of final variable. Any attempt to modify the final variable results in
compilation error. The error is as
follows
“final variable cannot be assigned.”
Can we create constructor in abstract class ?
We can create constructor in abstract class , it does’nt give any
compilation error. But when we cannot
instantiate class there is no use in creating a constructor for abstract
class.
Can we have a method name same as class name in java?
Yes we can have method name same as class name it won’t throw
any compilation error but it shows a
warning message that method name is same as class name.
Can we override constructors in java?
Only methods can be overridden in java. Constructors can’t be
inherited in java. So there is no point of
overriding constructors in java.
Can Static methods access instance variables in java?
No.Instance variables can’t be accessed in static methods. When we
try to access instance variable in
static method we get compilation error. The error is as follows:
Cannot make a static reference to the non static field name
How do we access static members in java?
Instance variables and instance methods can be accessed using
reference variable . But to access static
variables or static methods we use Class name in java.
Can we override static methods in java?
Static methods can’t be overridden. If we have a static method in
superclass and subclass with same
signature then we don’t say that as overriding. We call that as
method shadowing.
Difference between object and reference?
Reference and object are both different. Objects are instances of
class that resides in heap memory.
Objects does’nt have any name so to access objects we use
references. There is no alternative way to
access objects except through references.
Object cannot be assigned to other object and object cannot be
passed as an argument to a method.
Reference is a variable which is used to access contents of an object.
A reference can be assigned to other
reference ,passed to a method.
Objects or references which of them gets garbage collected?
Objects get garbage collected not its references.
How many times finalize method will be invoked ? who invokes
finalize() method in java?
Finalize () method will be called only once on object. Before the
object gets garbage collected garbage
collector will call finalize() method to free the resources. Finalize()
method will be called only when object
is eligible for garbage collection.
