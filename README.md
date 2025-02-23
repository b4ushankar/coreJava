# coreJava
Corejava Definations
# Java Virtual Machine
JVM (Java Virtual Machine) – The JVM is a software engine that runs Java applications by converting bytecode into machine-specific instructions. It enables Java’s "Write Once, Run Anywhere" capability by abstracting hardware differences. The JVM also manages memory through garbage collection and optimizes performance using Just-In-Time (JIT) compilation.

# Java Runtime Environment
JRE (Java Runtime Environment) – The JRE is a collection of software required to run Java applications, including the JVM and essential libraries. It does not include development tools like the Java compiler. If you only need to run Java programs and not develop them, installing the JRE is sufficient.

# Java Development Kit
JDK (Java Development Kit) – The JDK is a complete package for Java development, including the JRE, compiler (javac), and debugging tools. It provides everything needed to write, compile, and run Java applications. Different versions of the JDK include Standard Edition (SE), Enterprise Edition (EE), and Micro Edition (ME).

# Classloader
Classloader – The Classloader is a part of the JVM that loads Java class files into memory when needed. It follows a **hierarchical delegation model**, starting from the Bootstrap ClassLoader to user-defined classloaders. This mechanism allows Java to load classes dynamically at runtime, reducing memory usage.

# Bytecode
Bytecode – Bytecode is an intermediate representation of Java source code, stored in .class files. It is not directly executed by the CPU but interpreted or compiled by the JVM. This makes Java applications portable across different operating systems without recompilation.

# Garbage Collection
Garbage Collection (GC) – Garbage collection is an automatic memory management feature of Java that removes objects that are no longer in use. The JVM periodically identifies and reclaims unused memory, preventing memory leaks. Different GC algorithms, such as Mark-and-Sweep and G1 Garbage Collector, optimize performance.

# Heap Memory
Heap Memory – The heap is a region of memory where Java stores objects created at runtime. It is divided into Young Generation (new objects) and Old Generation (long-lived objects). Proper memory management, including garbage collection, ensures efficient use of heap space.

# Stack Memory
Stack Memory – The stack is a small memory area used for storing method call details, local variables, and execution order. Each method call creates a new stack frame that gets removed once the method completes. Stack memory is faster but limited in size compared to heap memory.

# Encapsulation
Encapsulation – Encapsulation is an object-oriented principle that restricts direct access to class fields and forces controlled access via methods. It is achieved using private variables and public getter/setter methods. This improves security, maintainability, and data integrity in Java programs.

# Polymorphism
Polymorphism – Polymorphism allows a method or object to take multiple forms, making code more flexible and reusable. It can be achieved through method overloading (same method name, different parameters) and method overriding (subclass modifies superclass behavior). This concept is widely used in frameworks and design patterns.

# Abstraction
Abstraction – Abstraction hides complex implementation details and exposes only the necessary functionality. In Java, it is implemented using abstract classes (which have incomplete methods) and interfaces (which define a contract for classes to follow). This helps in designing modular and scalable applications.

# Interface
Interface – An interface in Java defines a set of methods that a class must implement, without providing method bodies. It supports multiple inheritance, which is not possible with classes. Interfaces are widely used in frameworks to achieve loose coupling and extend functionality.

# Abstract Class
Abstract Class – An abstract class is a class that cannot be instantiated and contains both implemented and unimplemented methods. It is used as a blueprint for other classes, enforcing a common structure while allowing flexibility. Abstract classes are useful when some behavior should be shared, but specific details should be defined in subclasses.

# Inheritance
Inheritance – Inheritance allows one class (child) to acquire properties and behaviors from another class (parent). It helps in reusing existing code, reducing redundancy, and improving maintainability. Java supports single inheritance with classes but allows multiple inheritance through interfaces.

# Exception Handling
Exception Handling – Exception handling is a mechanism to manage runtime errors in a structured way. Java provides try, catch, finally, throw, and throws to handle different types of exceptions. Proper exception handling improves application stability and prevents crashes.

# Synchronization
Synchronization – Synchronization ensures that multiple threads do not access shared resources simultaneously, preventing data inconsistency. It is implemented using the synchronized keyword or the Lock interface. Proper synchronization is crucial for writing concurrent and thread-safe applications.

# Lambda Expression
Lambda Expression – A lambda expression is a concise way to write anonymous functions in Java. Introduced in Java 8, it allows functional-style programming and reduces boilerplate code. Lambdas are commonly used in streams, functional interfaces, and event handling.

# Streams API
Streams API – The Streams API provides a functional approach to processing collections of data. It allows operations like filtering, mapping, and reducing elements in a declarative way. Streams can also be parallelized to improve performance on multi-core processors.

# Reflection API
Reflection API – Reflection allows Java programs to inspect and manipulate classes, methods, and fields at runtime. It is commonly used in frameworks, libraries, and tools like Spring and Hibernate. However, excessive use of reflection can impact performance and security.

# Serialization
Serialization – Serialization is the process of converting an object into a byte stream for storage or transmission. Deserialization reconstructs the object back into memory when needed. Java provides the Serializable interface to enable object serialization.

# Java Collections Framework
Java Collections Framework (JCF) – The Java Collections Framework provides built-in data structures such as List, Set, and Map to manage and manipulate data efficiently. It includes implementations like ArrayList, HashSet, and HashMap. Collections simplify programming by offering ready-to-use algorithms for sorting, searching, and iterating over data.

# Generics
Generics – Generics allow classes and methods to work with different data types while ensuring type safety. They prevent ClassCastException by enforcing type checking at compile-time. Common examples include List<T>, Map<K, V>, and generic methods.

# Annotations
Annotations – Annotations provide metadata about code and are used for configuration, documentation, and runtime processing. Examples include @Override (ensures method overriding), @Deprecated (marks outdated methods), and @SpringBootApplication (used in Spring Boot applications). Custom annotations can also be created for specific use cases.



