# GenesisTest
Coding test for Genesis technical Systems

# General instructions:
Under the resouces directory you will find a file called input.xml, which contains xml values. These values represent data in the
the system that must be read in from disk, and instanciated as a collection of classes or structures that can have operations performed
on them.

The program should read the input.xml and place the resulting objects or structures that the file describes into some kind of collection.
After this has been achieved the program should create a command prompt waits for and reads in user imput. The return key is the sygnal to execute
the command.

The availible commands should include 'find','find by','stop', 'display current', 'display next',
'display previous' and 'display all'.

The 'find' command should find the object or structure that is defined by it's unique key value, and print it out in a formated human readable way.
The 'find by' command should find all objects that match the values supplied, and print them in the same manner.
Display current should display the first object in the collection, until 'display next' is called.

After 'display next' is called, the 'display current' command should then display the item that was last displayed and 'display previous' should then
display the first item. After 'find' is executed 'display next' should display the next item after that item, and so on.

If you have time you can also impliment a 'load' command and a 'reorder by' command.

Your program should be able to deal with errors in xml formating without failing by telling the used that there is an invalid xml elemt. As a further
excersise, if you have time, think about how you might correct the errors?

All 'display' commands need initially print out the structures in alphabetical order or such that a set of imaginary keys {a,aa,ab,abb,abbc,abcd} would be
ordered as in this example. By first letter first, then by next leter, etc, in ascending order.

Finally, consider how you could usefully expand this functionality?

There is no time limit on this excersise, but it should be completed in a reasonable time frame such that if you where doing it as a payed project,
your customer would be satisfied.

1. This project should be implimented in one of the following languages C, C++, or java.
2. You will need to proved a build system for your project that
    2.1. Builds the project.
    2.2. Runs the unit test without needing to execute your 'main' function.
    2.3. Additionaly, if it is written in c or c++ and you have the time, provide a function through your build system that
         that checks for memory leaks, and reports what it finds.
3. You may use any availible xml processing library to achieve the functionality of the program, or if you wish, impliment your own translation system.
4. You may use any availible collection, either suppled as part of the compiler or availible as open source,
however, if you have time, extra credit will be given if you impliment your own.


# Instructionns for java implementations
1. If you are implimenting in java, the input.xml file sould not be moved into the src/resources directory but read in form the directory where it is located.
