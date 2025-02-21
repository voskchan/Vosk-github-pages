# E-Portfolio
## CS 499 Capstone


My name is Chance Vosk, I majored in Computer Science at Southern New Hampshire University. This page was built to showcase some of my work that I have created during my time at SNHU. Below are three artifacts that I have enhanced in order to showcase my abilities.


# Table of Contents
1. Self Assessment
2. Code Review
3. Software Design and Engineering: CS 320 Appointment Tracker
4. Algorithms and Data Structure: CS 405 File Encryption
5. Databases: CS 340 Grazioso Salvare Database


## Self Assessment

Through my time at SNHU studying Computer Science I have gained many skills and abilities that have enhanced my coding performance. My courses here have given me a strong basis on learning how to collaborate in a team enviroment. Specifically my CS 310 work where we were tasked with working together in one code base through Bitbucket. This course helped me to understand how to code in order to prevent overlap of code from other team members and how to perform code reviews on other team members work. 

One of the other skills I have learned is how to communicate with stakeholders. In my CS 250 class I learned about the software development lifecycle and for part of the class took on the role of a project manager tasked with communicating with stakeholders. Through this course I learned how to gather software requirements and communicate the development progress with stakeholders in order to show progress on a project. 

All of my courses here at SNHU also taught me to produce code that is easily readable and well documented. My projects throughout my curriculum have strengthed my ability to design software by presenting me with projects in order to challenge my thinking on how to achieve the goal. The classes have also taught me a variety of coding languages that I have become more familiar with now, letting me code in more enviroments with ease. Many of my later classes have focused on projects that integrate databses in some way and has led me to learn how to leverage databses in order to track data and present it in a easy to read form. 

The artifacts presented below showcase the improvements in my strengths from earlier work in my classes. These artifacts also showcase my strengths in software design, algorithms, and databases. As I am focused on a Full Stack Development career these are all very important skills to have and these artifacts showcase my proficiency in them. These also showcase my ability to code across a variety of languages and create code that can be easily reused.

## Code Review


## Software Design and Engineering: Appointment Tracker

The artifact I chose for this category was the Appointment tracker I created in CS 320. This application was originally created to learn JUnit testing and did not have much actual user functionality. The JUnit test were designed to fully cover the code to showcase how they can be used for automated testing so user functionality was not necessary for the purposes of the assignment.

I chose to enhance this artifact as it allowed me to demonstrate my abilities to create software with user functionality as well as create automated testing for the code to ensure it will stay working throughout future updates. I also chose this for the challenge of updating the application to link an appointment with a contact as well as create a way for a user to interface with the application. 

The improvements I made to this code were:
- Creation of a ServiceDriver class for running application
- User Interface through command application
- Addition of Contact requirement when creating an Appointment
- Additional JUnit tests to further cover edge cases

During the process of enhancing this artifact I was able to see how much progress I have made in my coding ability. The original test cases for the project did pass a coverage test for the entire code but when it came to actual test cases it left many possibilities for failure open. Returning to these tests I was able to see the issues with them having more experience than I had when I created the code. Creating the ServiceDriver class to run the application was also an area of big improvement. In the original implementation there was not a way to keep a Contact list and an Appointment list running at the same time. by creating the ServiceDriver class I was able to resolve this issue and allow for an application that keeps track of both. 

This artifact improvement helped me to reach course outcomes 1, 2, and 4. By creating clean code that is well commented I can help to build a collaborative enviroment for any team that could be potentially working with my code later. It also achieves professional level communications adapted for the audience that will be working with the code. By creating the ServiceDriver class I was able to use my abilities to create a well-founded solution to the problem of the artifact not having any sort of user interface. 

## Algorithms and Data Structure: File Encryption

The artifact I chose for this category was my work in file encryption in CS 405. The original creation of this application took an input file and then, using a hardcoded password, performed an XOR cipher on the file. It then output the file as two seperate files, one encrypted and the other decrypted from running the XOR xipher again. I chose this artifact as it showcases my ability to create secure code and create a more secure cipher.

The original creation of this code was missing checks to ensure there was an actual input file. It also used a hard coded password. In longer messages with an XOR cipher this can result in a potential pattern that can be broken. The enhancements I made to this artifact are:
- File checks in order to prevent crashes
- Randomized key generation for cipher
- Key generation to the length of text to prevent pattern breaking
- Addition of a new seperate key file to track generated key

## Databases: CS 340 Grazioso Salvare

The artifact I chose for this category was my work in CS 340. In the original creation of this work I created a website linked to a database. This database was used to display animals in shelters that could be potential candidates for the company to use for rescue operations. I chose to use this as my artifact as it would showcase my ability to create a databse as well as link this database to a program to display information.

As the original creation of this work was made in the apporto virtual lab the code was created to run on a linux based enviroment. The main problem I had to overcome with this project was recreating the project within a windows enviroment and running the project. The other problem I encountered was that I no longer had access to the database that the work pulled from  
