# Genesis Test
This is a coding test for Genesis Technical Systems.

## Notes
Anything that is marked as 'additionally' is there to indicate a feature that is not required, but that if you are able to implement will impress us.

Anything that is marked ‘should’ be deemed to be to a requirement of the finished project.

Anything that is marked 'specifically' is deemed to be import and special attention should be paid to this.

Unless a specific mechanism or paradigm is specified you are free to achieve your design goals by using functionality either available in the language or its supplied libraries, functions, or any open-source implementation to achieve your goal.

Finally, this brief has been designed to be challenging in multiple ways. It is given to you so that we might gain some insight into how you think, so that we can decide if you would be a good and add value here at Genesis. 
There are often no perfect answers to design problems, but a simple, efficient solution that meets all the requirements of the brief will always be well received.

## General advice:
Think carefully about what the program is trying to achieve?

Specifically, what problem is it trying to solve?

If at any point you genuinely feel that you are stuck and are unable to make progress, it is better to reach out to your recruiter for help than to stagnate. 

The solution you deliver will be judged on:
1. Technical merit.
2. Innovation and imagination.
3. Code structure and attention to detail.
4. Adherence to requirements.
5. Design and implementation process.

You should aim to make your implementation as robust as you can. This means that it should not unexpectedly fail when given incorrect input, and if it does fail, your program should at least try to recover, and fail gracefully.

It should be designed and implemented as though for an external customer who is paying you for a fixed fee for your work (not an hourly rate). When thinking of features that you might implement, you should approach this in the same way. Ask yourself how would the feature be useful to my customer? How does it add value the project? Will I be able to deliver this in a timely fashion? How easy is it to use?

It is left up to you how you plan and manage your time, and additionally, how you would communicate your ideas and intentions. How would you communicate you design process to your client?

You are advised to think carefully about how you are going to approach this task. Additionally, if you make specific design decisions or use a specific design process, you might wish to document this in some way and include it as part of your submission. A directory call 'documents' is provided for this purpose. You are free to add documents in any format, however bear in mind accessibility.

You are free to ask questions by emailing recruitment@genesistechsys.com. Please include your name in the email so that we can identify you from your CV.

If you get stuck on a feature, but you have implemented other functionality, and you feel that you have taken too much time, you are free to submit what you have been able to achieve. In this event your submission should provide some rational output that servers to demonstrate that the features functions in the way intended.

There is no specific time limit on this exercise, but in practical terms you should be able to complete the brief in no more than three working days (where each working day would be 7.5 hours, and you would be able to dedicate 75% of your time to planning and executing the tasks). In real terms we will expect you to complete the task no later than one week of receipt of this brief, unless you have asked for more time giving specific reasons such as work commitments. 

At any rate, it needs to be completed in a reasonable amount of time such that if you were doing it as a paid project with a fixed fee, your customer would be satisfied with his purchase.

Finally, this brief has been left open ended in many regards to allow you the latitude to be creative and so that we can assess you process. This means that some of the details of design and implementation are left up to you. However, you should at least plan to implement all features that are described as 'should'.

## Brief:
Under the resources directory you will find a file called input.xml. This contains xml values that represent structures or objects in an imaginary system. The program needs to read in the file from disk, decode it into objects or structures, and place the products of that function into a collection so that operations can be performed at the next stage.

Your collection needs to initially be ordered by key value, alphabetically, such that a set of imaginary unordered keys s1={bbcb,a,abb,ab,bac,aa} becomes the ordered set s2={a,aa,ab,abb,bac,bbcb}. By first letter, then by next latter and word length, etc, in ascending order.

The program needs to make available the commands 'find’, ‘find by', 'stop', 'display current', 'display next', 'display previous' and 'display all'.

The 'find' command should find the object or structure by it's unique key value, and display it in a human readable format. The 'find by' command should find all objects or structures that match some set of values. The complexity of this function, and how it is implemented, is left up to you.

Additionally, if you have time, consider implement a 'load' command and a 'reorder by' command?

## Specific Instructions:
1.	This project should be implemented in one of the following languages C, C++, or java.
2.	You will need to prove a build system for your project that:
3.  Your build system should Builds the project so that it can be executed and run by your customer in the simplest way possible.
4.  Additionally, if you're build systems doesn't already do this, you might wish to execute any functional tests you have provided from the build system.
5.  Additionally, if you are implementing in c or c++ you might want to provide a function through your build system that that checks memory use, and reports errors.
6.	DO NOT COMMIT YOUR PROJECT TO THE SAME REPOSITORY YOU GOT THE BRIEF FROM.

## Submission instructions
This project needs to be submitted as a link to your code in an accessible repository such as GitHub. If you do not have a GitHub account (or similar) you should create one. This is free to do and will serve you well in your career as a software engineer.
Your submission should be added to a repository named genesis-test-candidate-first-name.candidate-second-name.

After you have done this the URL should be sent to recruitment@genesistechsys.com

## Instructions for java implementations
If you are implementing in java, the input.xml file should not be moved into the src/resources directory, but should be readable form the directory it is currently in.
