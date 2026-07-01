# Java-Pract-Code
Java is a high-level, robust, object-oriented, and secure programming language as well as a platform. It was developed by Sun Microsystems (now owned by Oracle) in 1995, and James Gosling is known as the father of Java.

🔹 What is a Platform?
A platform is any hardware or software environment in which a program runs.
Java is considered a platform because it comes with its own Java Runtime Environment (JRE) and Application Programming Interface (API).
🔷 Applications of Java
According to Sun Microsystems, over 3 billion devices run Java.
It is used in various domains, such as:
	1. Desktop Applications – Acrobat Reader, Media Player, Antivirus
	2. Web Applications – IRCTC, JavaTpoint, etc.
	3. Enterprise Applications – Banking systems, etc.
	4. Mobile Applications
	5. Embedded Systems
	6. Smart Cards
	7. Robotics

Advantages of Java
• Platform independent: Java code can run on any platform that has a Java Virtual Machine (JVM) installed, which means that applications can be written once and run on any device.
• Object-Oriented: Java is an object-oriented programming language, which means that it follows the principles of encapsulation, inheritance, and polymorphism.
• Security: Java has built-in security features that make it a secure platform for developing applications, such as automatic memory management and type checking.
• Large community: Java has a large and active community of developers, which means that there is a lot of support available for learning and using the language.
• Enterprise-level applications: Java is widely used for developing enterprise-level applications, such as web applications, e-commerce systems, and database systems.

Disadvantages of Java
1. Performance: Java can be slower compared to other programming languages, such as C++, due to its use of a virtual machine and automatic memory management.
Memory management: Java’s automatic memory management can lead to slower performance and increased memory usage, which can be a drawback for some applications.


🔷 What is Bytecode in Java?
Bytecode is an intermediate code generated between the compilation and the execution of a Java program.
	
Definition: Bytecode is a non-human-readable code that the Java Compiler generates from .java source code. This bytecode (in .class file format) is interpreted and executed by the Java Virtual Machine (JVM).

1️⃣ Java Virtual Machine (JVM)MOST IMPORTANT
	• Definition: 
	JVM (Java Virtual Machine) is an abstract machine.it is called virtual machine because it does not physical exist. It is a specification that provides runtime environment in which java bytecode can be executed.
	JVMs are available for many hardware and software platforms (i.e. JVM is platform dependent).
	• Role:
		○ Converts Java bytecode into machine code.
		○ Can also run bytecode from other languages compiled to Java bytecode.
		○ Acts as a virtual machine, meaning it doesn't exist physically.
	• Part of: JVM is part of the Java Runtime Environment (JRE).
	• Platform Independence: Each OS has its own JVM, making Java platform-independent.
	• Key Functions:
		The JVM performs following operation:
			§ Loads code
			§ Verifies code
			§ Executes code
			§ Provides runtime environment
		JVM provides definitions for the:
			§ Memory area
			§ Class file format
			§ Register set
			§ Garbage-collected heap
			§ Fatal error reporting etc.

    2️⃣ BytecodeMOST IMPORTANT
	• Definition: 
	Bytecode is an intermediate code generated between the compilation and the execution of a Java program.
	Definition: Bytecode is a non-human-readable code that the Java Compiler generates from .java source code. This bytecode (in .class file format) is interpreted and executed by the Java Virtual Machine (JVM). 
	• Features:
		○ Stored in .class files
		○ Platform-independent – can run on any system with JVM
Executed by JVM, not by the underlying OS directly

3️⃣ Java Development Kit (JDK)MOST IMPORTANT
	• Definition: The Java Development Kit (JDK) is a software development kit used to develop Java applications 
	• Contains:
		○ JRE (Java Runtime Environment)
		○ Development tools like javac, java, javadoc, jar, etc.
	• Physical Existence: Yes, it is installable on platforms like Windows, Linux, macOS.
	• Includes Support For:
		○ Java SE (Standard Edition)
		○ Java EE (Enterprise Edition)
		○ Java ME (Micro Edition)

4️⃣ Java Runtime Environment (JRE)MOST IMPORTANT
	• Definition: JRE stands for Java Runtime Environment. The Java Runtime Environment (JRE) is a set of software components that allows Java programs to run on a computer's operating system
	• Contains:
		○ JVM
		○ Libraries
		○ Class files, supporting files
	• Use Case:
		○ For running Java programs, JRE is enough.
For developing, JDK (which includes JRE) is required.

5️⃣ Garbage CollectionMOST IMPORTANT(VERY IMPORTANT)
	• Definition: Garbage collection in Java is the process by which Java programs perform automatic memory management.
	• How It Works:
		○ Java programs create objects on the heap.
		○ Over time, some objects are no longer needed.
		○ The Garbage Collector identifies and removes these unreferenced objects, freeing memory.
Garbage collection in Java is the process by which Java programs perform automatic memory management. Java programs compile to bytecode that can be run on a Java Virtual Machine. When Java programs run on the JVM, objects are created on the heap, which is a portion of memory dedicated to the program. Eventually, some objects will no longer be needed. The garbage collector finds these unused objects and deletes them to free up memory.

6️⃣ Class Path
	• Definition: Class path is the location or file path used by the Java compiler and JVM to locate .class files.
	• Details:
		○ By default, JDK includes standard libraries.
		○ To use external libraries, you must manually add them to the classpath.
Concept: In Java, everything is treated as a class, and the classpath tells Java where to find these classes.

🧾 What Are Data Types in Java?(VERY IMPORTANT)
Data types define the type of value a variable can store and what kind of operations can be done on it.
						                 OR
In Java, data types define the type of data that can be stored in a variable. They determine the size and kind of values that variables can hold and the operations that can be performed on them.

Primitive Data Types in Java
Primitive data are only single values and have no special capabilities.  Primitive data types are the most basic and predefined data types in Java. They store simple values and are directly mapped to memory.

Characteristics
	•  Fixed Size → Har primitive type ka size predefined hota hai 
	•  Fast Performance → Direct value store karte hain, isliye access fast hota hai 
	•  Store Simple Values → Number, character, true/false jaise data 
	•  Predefined by Java
Stored directly in memory

Non-Primitive (Reference) Data Types
The Non-Primitive (Reference) Data Types will contain a memory address of variable values because the reference types won’t store the variable value directly in memory. They are strings, objects, arrays, etc.
Non-primitive data types are user-defined types that are more complex and capable of storing multiple values.it is also called reference data types.
These data types store references to objects, not actual values.

Characteristics of Non-Primitive (Reference) Data Types
✅ Size is not fixed (can be dynamic)
✅ Can store multiple values
✅ Can create complex data structures
✅ Support methods and additional functionalities
✅ Accessed through references (memory addresses)

What is a Variable in Java?(MOST IMPORTANT 🔥🔥)
A variable is a named memory location used to store data values.It acts as a container that holds data during program execution.

A variable in Java is a named memory location used to store data that can be changed during program execution. 

🔹 Rules for Naming Variables in Java	(MOST IMPORTANT 🔥🔥)		
✅ Can contain: letters, numbers, _, $
✅ Can’t start with a number
✅ Must not be a Java keyword
✅ Case-sensitive (Age ≠ age)
✅ Use meaningful names (e.g., studentName, totalMarks)

1. Local Variables(MOST IMPORTANT 🔥🔥)
Variables defined inside methods, constructors or blocks are called local variables.

	• Declared inside methods, constructors, or blocks.
	• Created when the method/block is entered and destroyed when exited.
	• Scope is limited to that block or method only.
	• Must be initialized before use.
	• It is created on stack memory.
	• This variables accessible only within method/constructor/class in which they are created.
It is accessible only variables name .

2. Instance Variables(MOST IMPORTANT 🔥🔥)
Variables defined inside a class but outside any method, constructor or block are known as instance variable.no static keyword use.
Instance variables are known as non-static variables and are declared in a class outside of any method, constructor, or block. 

	• Declared inside a class but outside any method, constructor, or block (no static keyword use).
	• Each object of the class has its own copy.
	• Created when the object is created and destroyed when the object is destroyed.
	• Can have access modifiers (public, private, etc.).
	• Default values are assigned if not initialized (0 for int, null for objects).
	Initialization of instance variable is not compulsory
	• It is created on heap memory.
	• Accessed via object references.
