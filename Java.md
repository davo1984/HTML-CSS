# Java   
Java is a high-level, compiled, strongly typed OOP lang.
- High-level: code is easily human-readable, unlike binary, assembly...
- Compiled-language: Human-readable code (source code) is *compiled*, or transformed, into a form more optimized for computers to read (eg binary, in the case of Java: **bytecode**)
    - For ex, C++ code is compiled into binary
    - Java code is compiled into **bytecode**, which the Java Virtual Machine (JVM) will then interpret.
- Strongly-typed: variables declared of a certain type can only have values assigned to it of that same type
- Object-oriented: Java revolves around the use of classes (which are basically blueprints for objects), and objects themselves

## Why Java?
- One of the most in-demand languages in the world
- Over 20 years in the industry
- Powering over 3 billion devices
- #1 server-side web technology (backend)

## Benefits
- Platform Independent (write once, run anywhere)
    - made possible through the JVM
        We have different JVMs for different OSes
            - Mac
            - Windows 
            - Linux
            - Android
            - etc.
        - So all we need to run the same program on different operation systems is simply to havethe correct JVM for our OS
- C-language inspired syntax
- Automatic memory management
    - Garbage Collector (gc)
        - frees up memory automatically that is not being used
- Extensive built-in runtime library
- Rich open-source community

# Java 8 Features
Added features such as 
- Lambda expressions
- Method references
- Functional interfaces
- Stream API
- Default methods in interfaces
- Collectors class
-etc

# JVM vs JRE vs JDK
In order to write and run Java we need to have an understanding of the JVM, JRE, and JDK. In particular, understanding these different components make up the core ability to run & write Java programs sets a foundation for what it means to use Java.

- JVM (Java Virtual Machine): Enables a computer to run Java programs. Behaves as a interpreter that essentially takes bytecode and translates it to a lower level that the computer itself can understand.
- JRE (Java Runtime Env): Contains the JVM & runtime libraries that our code may be using. If all we want to do is run Jaa programs, all we need to do is install the JRE.
- JDK (Java Dev Kit): Contains the JRE + developer tools (javadoc), and other command-line utilities

If we want to both run and write programs, we should install a JDK. If we only want to run Java programs (eg. we wanted to play Java Minecraft) we would install a JRE.

## Write Once Run Anywhere (platform independence)
Platform independence is established by the JVM. We really only need to compile the code once from source code into bytecode, which will then allow for us to run our Java program on any operating system,  any machine, as long as we have the correct JVM installed for that particular operating system. For example, I can develop and compile my code on Windows into bytecode, but if I have a Mac compatible JVM, I should be able to run the bytecode over on the Mac machine as well.
