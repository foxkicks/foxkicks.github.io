---
title: Professional Self-Assessment
categories: [SCHOOL]
tags: [capstone, self-assessment]
---

#### Discuss how completing your coursework throughout the program and developing the ePortfolio has helped you showcase your strengths, shape your professional goals and values, and prepare to enter or become more employable in the computer science field.

During this course, I was given the oppertunity to showcase my strengths in the form of recreating a program from scratch and adding new functionality to it.
For the first part, I created a GUI for the software via WinForms that includes both buttons and input fields. For the second enhancement, I added algorithms that
took elements from a vector to calculate the accumulated fees for a pet that was checking out. In the third enhancement, I added database functionality to ensure
that the data entered would be persistent. It's still an incomplete program with a long ways to go to be useful for any specific company, but it does show that I can
cook up a decent tool in a small span of time.

When collaborating in a team environment, I make sure to communicate my intentions before committing to them to ensure that I am not performing double-work or
doing something unnecessary. My code is also thoroughly commented for the sake of being revisited by myself or others. The comments describe functionality and
connections to other pieces of the code. When working on a group project, I am flexible enough to fit any specific role. From my group project in my game development
course, I know that I can potentially put out more work than the rest of the group.

Stakeholders are important to software development. They are the ones that we need to please, the ones that are either funding the program or will use the program.
It is important to fit the needs of the stakeholders without compromising the purpose of the project. It's also important to keep them in the loop when developing a
project. They will want to know each functional change to the project, but maybe not every small bugfix. When making a program for a friend, I considered him as a
stakeholder. I developed the program I believed would be satisfactory, then took his feedback and made the adjustments as necessary. It is important to filter feedback,
unless the stakeholder is the main funding and gives you no choice in the matter.

Data structures and algorithms are important to any program. Data structures store all of the information needed for specific functions. I usually use vectors to store
data, but sometimes I use hash maps when the order doesn't matter because they are more efficient. Algorithms are meant to do the repetitive dirty work for a program.
It's good practice to keep algorithms nested within their own functions so that they can be routinely called when needed, especially if they need to be called more than once.
When using algorithms, it's good practice to not use "magic numbers" for constants. Naming the constants improves readability of the code, giving every constant a descriptive name.
For the Pet Service program, an algorithm was used to calculate the check-out fee for the pets.

I've worked on two separate full-stack applications now, doing work on both backend and frontend. The frontends were using Angular and the backends used either MongoDB or DynamoDB.
MongoDB was used for a locally hosted web application and DynamoDB was used for an AWS Cloud application. I can successfully engineer a web application that has regular database
interaction. I can make an application with full CRUD functionality, which means I can work pretty well with databases. I know the differences between SQL and NoSQL, as well as MongoDB
and DynamoDB. I've also used SQLite3 in personal projects due to it's simplicity and the lack of a need for scalability.

Security in most applications comes in the form of input validation and access roles. Input validation is important for keeping a program stable and preventing it from giving out
unnecessary information. Access roles are when you define the difference between a guest, a user, and an administrator. Access roles can be split even further, but those are the basic roles.
Guests typically have low access, but can some non-critical parts of a web application. Users and admins will require login authentication with encryption. Users get basic access to
consumer functionality, while admins would get full access to modify pages of the web application and the ability to interact with the database(s).

#### Summarize and introduce how your artifacts fit together and inform the portfolio as a whole.

I used one artifact for all three enhancements, meaning that each enhancement is built from the previous one, except the first. These artifacts were enhanced in a specific order:
software design -> data structures & algorithms -> databases. For software design, I recreated the intended program in a WinForms project that uses C# instead of Java. This is more
of a preference due to my experience with WinForms and the easy-to-use designer that Visual Studio comes with. For the second category, data structures & algorithms, I employed the
use of a vector to store the data for Pets, and used an algorithm to handle pet fees. In the final stage, I added a database to properly store the pet information, as well as the ability
to add and remove items from it via the Check-In and Check-Out buttons. Through each step, I prove that I can perform vital tasks as a software engineer.
