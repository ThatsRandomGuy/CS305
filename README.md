# CS305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a branch of the company Global Rain. They were looking to find a secure method for ensuring that user's data was encrypted to prevent potential attackers from gaining access.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I think what I did well was creating each new encryption key. Coding securely is a good practice to learn because it prevents attackers from gaining access to things you never intended people to have access to. Even if it is a small program that does not hold data, there is potential for damage to be done by attackers. It is best to avoid this all together by following secure coding practices. Software security allows users to trust companies and be confident that their data is not being thrown all over the place.

Which part of the vulnerability assessment was challenging or helpful to you?
The only challenging part of vulnerability assessments is finding out what is a real threat and what is a false-positive. This is not even that challenging thanks to the internet and one simple search can help you determine whether or not something is a risk. This, however, takes a lot of time with bigger projects that use many different libraries that could have potential vulnerabilities.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The main method of increasing security was using encryption keys to ensure that data could not be accessed by someone that should not have access to it. It is important to find which security methods are best for each use case. Some situations require more security than others and should be treated differently. Using something like a Maven check is also really useful in finding potential security vulnerabilities that visual checks might miss.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To make sure the code was funcional I ran the code and fixed any errors that popped up in the console. To make sure it was secure, I ran Maven checks to determine potential vulernabilites and look into each just to be sure. After refactoring the code, I ran another Maven check to see if new libraries introduced new vulnerabilities.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Maven checks are something that I can see myself using for a long time to come. They allow the user to identify things that would otherwise go right over your head. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show them that I know how to use Maven checks, and I know what to look for when reviewing them. I also would show them that I know how to use encryption keys to keep information secure and private for potential clients down the road.
