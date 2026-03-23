## 何为python，为何python

- 官网：https://www.python.org/about/

Python is powerful... and fast;  plays well with others;  runs everywhere;  is friendly & easy to learn;  is Open.
<br>These are some of the reasons people who use Python would rather not use anything else.

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/c61ec634-2b93-4848-ac1b-e10207ab9362" />


[what-is-python] https://docs.python.org/3/faq/general.html#what-is-python 
##### 1.What is Python?
<br>Python is an interpreted, interactive, object-oriented programming language. 
<br>It incorporates modules, exceptions, dynamic typing, very high level dynamic data types, and classes. 
<br>It supports multiple programming paradigms beyond object-oriented programming, 
<br>such as procedural and functional programming. 
<br>Python combines remarkable power with very clear syntax. 
<br>It has interfaces to many system calls and libraries, as well as to various window systems, 
<br>and is extensible in C or C++. 
<br>It is also usable as an extension language for applications that need a programmable interface. 
<br>Finally, Python is portable: it runs on many Unix variants including Linux and macOS, and on Windows.

<br>To find out more, start with The Python Tutorial. The Beginner’s Guide to Python links to other introductory tutorials and resources for learning Python.


##### 2.Why was Python created in the first place?
Here’s a very brief summary of what started it all, written by Guido van Rossum:
> <br>I had extensive experience with implementing an interpreted language in the ABC group at CWI, and from working with this group I had learned a lot about language design. This is the origin of many Python features, including the use of indentation for statement grouping and the inclusion of very-high-level data types (although the details are all different in Python).
> <br>I had a number of gripes about the ABC language, but also liked many of its features. It was impossible to extend the ABC language (or its implementation) to remedy my complaints – in fact its lack of extensibility was one of its biggest problems. I had some experience with using Modula-2+ and talked with the designers of Modula-3 and read the Modula-3 report. Modula-3 is the origin of the syntax and semantics used for exceptions, and some other Python features.
> <br>I was working in the Amoeba distributed operating system group at CWI. We needed a better way to do system administration than by writing either C programs or Bourne shell scripts, since Amoeba had its own system call interface which wasn’t easily accessible from the Bourne shell. My experience with error handling in Amoeba made me acutely aware of the importance of exceptions as a programming language feature.
> <br>It occurred to me that a scripting language with a syntax like ABC but with access to the Amoeba system calls would fill the need. I realized that it would be foolish to write an Amoeba-specific language, so I decided that I needed a language that was generally extensible.
> <br>During the 1989 Christmas holidays, I had a lot of time on my hand, so I decided to give it a try. During the next year, while still mostly working on it in my own time, Python was used in the Amoeba project with increasing success, and the feedback from colleagues made me add many early improvements.
> <br>In February 1991, after just over a year of development, I decided to post to USENET. The rest is in the Misc/HISTORY file.

##### 3.What is Python good for?
Python is a high-level general-purpose programming language that can be applied to many different classes of problems.
<br>The language comes with a large standard library that covers areas 
<br>such as string processing (regular expressions, Unicode, calculating differences between files), 
<br>internet protocols (HTTP, FTP, SMTP, XML-RPC, POP, IMAP), 
<br>software engineering (unit testing, logging, profiling, parsing Python code), 
<br>and operating system interfaces (system calls, filesystems, TCP/IP sockets).
<br>Look at the table of contents for The Python Standard Library to get an idea of what’s available.
<br>A wide variety of third-party extensions are also available. Consult the Python Package Index to find packages of interest to you.



##### 3.Is Python a good language for beginning programmers?
Yes.

<br>It is still common to start students with a procedural and statically typed language such as Pascal, C, or a subset of C++ or Java. Students may be better served by learning Python as their first language. Python has a very simple and consistent syntax and a large standard library and, most importantly, using Python in a beginning programming course lets students concentrate on important programming skills such as problem decomposition and data type design. With Python, students can be quickly introduced to basic concepts such as loops and procedures. They can probably even work with user-defined objects in their very first course.
<br>For a student who has never programmed before, using a statically typed language seems unnatural. It presents additional complexity that the student must master and slows the pace of the course. The students are trying to learn to think like a computer, decompose problems, design consistent interfaces, and encapsulate data. While learning to use a statically typed language is important in the long term, it is not necessarily the best topic to address in the students’ first programming course.
<br>Many other aspects of Python make it a good first language. Like Java, Python has a large standard library so that students can be assigned programming projects very early in the course that do something. Assignments aren’t restricted to the standard four-function calculator and check balancing programs. By using the standard library, students can gain the satisfaction of working on realistic applications as they learn the fundamentals of programming. Using the standard library also teaches students about code reuse. Third-party modules such as PyGame are also helpful in extending the students’ reach.
<br>Python’s interactive interpreter enables students to test language features while they’re programming. They can keep a window with the interpreter running while they enter their program’s source in another window. If they can’t remember the methods for a list, they can do something like this:
