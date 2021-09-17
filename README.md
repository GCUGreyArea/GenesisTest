# GenesisTest
This is a coding test for Genesis Technical Systems.

# Notes
Anything that is marked as 'aditionally' is there to indicate a feature that is not required, but that if you are able to impliment will impress us.

Anything that is marked is 'should' is deamed to be to a requirement of the finished project.

Anything that is marked 'specifically' is deamed to be import and special attention should be paid to this.

Unless a specific mechanism or paradigm is specified you are free to achieved your design goals by using functionality either availible in the language or its supplied libraries, functions, or any open source implimentation to achieve your goal.

Finally, this breif has been has been designed to be chalangig in multiple ways. It is given to you so that we might gain some insight into how you think, so that we can decide if you would be a good and add value here at Genesis. There are often no perfect ansewrs to design problems, but a simple, efficient solution that meets all the requirements of the brief will always be well received.

# General advice
Think carefully about what the program is trying to achieve?

Specifically, what problem is it trying to solve?

You shoud aim to make your implimentation as robust as you can. This means that it should not unexpectedly fail when given incorrect input, and if it does fail, your program should at least try to recover, and fail gracefully.

It should be designed and implimented as though for an external customer who is paying you for a fixed fee for your work (not an hourley rate). When thinking of features that you might impliment, you should approach this in the same way. Ask yoursef how would the feature be useful to my customer? How does it add value the project? Will I be able to deliver this in a timely fasion? How easy is it to use?

It is left up to you how you plan and manage your time, and additionally, how you would communicate your ideas and intentions.

You are advised to think carefully about how you are going to approcah this task. Aditionally, if you make specific design descisions or use a specific design process, you might wish to document this in some way and inculde it as part of your submition. A directory call 'documents' is provided for this perpose.

You are free to ask questions by emailing recruitment@genesistechsys.com. please include your name in the email so that we can identify you from your CV.

If you get stuck on a feature, but you have implimented other functionality, and you feel that you have taken too much time, you are free to submit what you have been able to achieve. In this event your submition should provide some rational output that servers to demonstrate that the features functions in the way intended.

There is no secific time limit on this excersise, but in practical terms you should be able to complete the brief in no more that three working days (where each working day would be 7.5 hours, and you would be able to to dedicate 75% of your time to planning and executing the taks). At any rate, it needs to be completed in a reasonable amount of time such that if you where doing it as a payed project with a fixed fee, your customer would be satisfied with his purchase.

Finally, this brief has been left open ended in many regards to alow you the latitude to be creative and so that we can asses you process. This means that some of the details of design and implimentation are left up to you. However, you should at least plan to impliment all features that are described as 'should'.

# Brief:
Under the resouces directory you will find a file called input.xml. This contains xml values that represent structures or objects in an imaginary system.
The program needs to read in the file from disk, decode it into objects or structures, and place the products of that function into a collection so that operations can be performed at the next stage.

Your collection needs to initially be ordered by key value, alphabetically, such that a set of imaginary unordered keys s1={bbcb,a,abb,ab,bac,aa} becomes
the ordered set s2={a,aa,ab,abb,bac,bbcb}. By first letter, then by next leter and word length, etc, in ascending order.

The program needs to make availible the commands 'find','find by','stop','display current','display next','display previous' and 'display all'.

The 'find' command should find the object or structure by it's unique key value, and display it in a human readable format.
The 'find by' command should find all objects or structures that match some set of values. The complexity of this function, and how it is implimented, is left up to you.

Aditionally, if you have time, consider impliment a 'load' command and a 'reorder by' command?

# Specific Instructionns
1. This project should be implimented in one of the following languages C, C++, or java.
2. You will need to proved a build system for your project that:
  *1.* Your build system should Builds the project so that it can be executed and run by your customer in the simplest way posible.
  *2.* Aditionally, if you're build systems doesn't already do this, you might wish to execute any functional tests you have provided from the build system.
  *3.* Additionaly, if you are implimenting in c or c++ you might want to provide a function through your build system that that checks memory use, and reports errors.
  *4.* DO NOT COMMIT YOUR PROJECT TO THE SAME REPOSITORY YOU GOT THE BRIEF FROM.

# Submition instructions
This project needs to be submited as a link to your code in an accessible repository such as github. If you do not have a github account (or similar) you should create one. This is free to do and wil serve you well in your carrer as a software engineer.

Your submition should be added to a repository named genesis-test-${candidate-first-name}.${candidate-second-name}.

After you have done this the URL should be sent to recruitment@genesistechsys.com

# Instructionns for java implementations
1. If you are implimenting in java, the input.xml file sould not be moved into the src/resources directory, but should be readable form the directory it is currently in.
