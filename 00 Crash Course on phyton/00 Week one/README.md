# Crash Course of Python - Week 1
In this module we’ll introduce you to the Coursera platform and the course format. Then, we’ll dive into the basics of programming languages and syntax, as well as automation using scripting. We’ll also introduce you to the Python programming language and some of the benefits it offers. Last up, we’ll cover some basic functions and keywords of the language, along with some arithmetic operations.

## Learning Objectives

* Navigate the Coursera platform and find resources for help
* Define what a programming language is and what syntax means
* Define what a script is and how it applies to automation
* List some of the benefits of the Python programming language
* Utilize basic functions and keywords to display data and perform arithmetic operations

---
* Understand what Python is
* Understand what scripting is
* Understand why Python is relevant to IT
* Understand the role of automation in IT
* Run your first Python script
---

---
## Course Introduction
### Welcome to the Course!
This course is designed to teach you the foundations of programming in Python. We’re excited to join you on this journey as you learn one of the most-in-demand job skills in IT today. In the U.S. alone, according to Burning Glass data from May 2019, there were ~530K job openings in 2018 asking for Python skills.
### Course prerequisites
This course requires no previous knowledge of programming. Familiarity with basic IT concepts, like operating systems, files and processes, networking and data management will be required in further courses. For learners with no IT background at all, we recommend taking the [IT Support Professional Certificate 101.](https://www.coursera.org/professional-certificates/google-it-support).
### How to pass the class
You can review videos, readings, discussion forums, in-video questions, and practice quizzes in the program for free. However, to access graded assignments and be eligible to receive your official Google IT Support certificate, you must:
* Pay the [course certificate fee](https://www.coursera.support/s/article/209818963-Payments-on-Coursera?language=en_US), or apply and be approved for [Coursera Financial Aid.](https://www.coursera.support/s/article/209819033-Apply-for-Financial-Aid-or-a-Scholarship?language=en_US).
AND
* Pass all graded assignments in the six courses at the minimum passing level, or above. Each graded assignment in a course is part of a cumulative grade for that course. The passing score for each course is 80%.
### How deadlines work
When you enroll in the course, the system automatically sets a deadline for when you need to complete each section. Heads up: These deadlines are there to help you organize your time, but you can take the course at your own pace. If you "miss" a deadline, you can just reset it to a new date. There’s no time limit in which you have to finish the course, and you can earn the certificate whenever you finish.
### Getting and giving help
Here are a few ways you can give and get help: 
* 1. Discussion forums: You can share information and ideas with your fellow learners in the discussion forums. These are also great places to find answers to questions you may have. If you're stuck on a concept, are struggling to solve a practice exercise, or you just want more information on a subject, the discussion forums are there to help you move forward.

* 2. Coursera learner support: Use the Learner Help Center to find information on specific technical issues. These include error messages, difficulty submitting assignments, or problems with video playback. If you can’t find an answer in the documentation, you can also report your problem to the Coursera support team by clicking on the Contact Us! link available at the bottom of help center articles.

* 3. Course content issues: You can also flag problems in course materials by rating them. When you rate course materials, the instructor will see your ratings and feedback; other learners won’t. To rate course materials:
      * Open the course material you want to rate. You can only rate videos, readings, and quizzes.

      * If the item was interesting or helped you learn, click the thumbs-up icon.

      * If the item was unhelpful or confusing, click the thumbs-down icon.

### Finding out more information
Throughout this course, we'll be teaching you the basics of programming and automation. We'll provide a lot of information through videos and supplemental readings. But sometimes, you may also need to look things up on your own, now and throughout your career. Things change fast in IT, so it’s critical to do your own research so you stay up-to-date on what’s new. We recommend you use your favorite search engine to find additional information— it’s great practice for the real world!

On top of search results, here are some good programming resources available online:

* The official [Python tutorial](https://docs.python.org/3/tutorial/index.html). This tutorial is designed to help people teach themselves Python. While it goes in a different order than the one we're taking here, it covers a lot of the same subjects that we explore in this course. You can refer to this resource for extra information on these subjects.

* The [Think Python](https://greenteapress.com/wp/think-python/) book. This book aims to teach people how to program in Python. It's available online in PDF and browsable forms. Again, you can use this resource to learn more about some of the subjects we cover.

The [official language reference](https://docs.python.org/3/reference/index.html). This is a technical reference of all Python language components. At first, this resource might be a little too complex, but as you learn how Python works and how it’s built, this can be a useful reference to understand the details of these interactions.

## Introduction to Programming
### What is programming?
At a basic level, a computer program is a recipe of instructions that tells your computer what to do. When you write a program, you create a step by step recipe of what needs to be done to complete a task and when your computer executes the program it reads what you wrote and follows your instructions to the letter.

```
Did you get all that? Let's check with a quick question!
Why do we need to learn the syntax and semantics of a programming language?
     * To be able to easily switch to a different programming language
     * So that we know which part is the subject and which one is the predicate
     * [CORRECT] To allow us to clearly express what we want the computer to do 
     * To understand why our computer crashes	
		
```

In a human language, __**syntax** is the rules for how a sentence is constructed__ while __**semantics** refers to the actual meaning of the statements__.
In a programming language, __the **syntax** is the rules for how each instruction is written__ and __the **semantics** is the effects the instructions have__.  

|   | Syntax | Semantic |
|:-|:-|:-|
| Human Language | the rules for how a sentence is constructed | refers to the actual meaning of the statements |
| Programming Language | the rules for how each instruction is written | the effects the instructions have |

What's the difference between a script and a program?  
* Scripts as programs with a short development cycle that can be created and deployed rapidly. In other words, a script is a program that is short, simple, and can be written very quickly.

### What is automation?
Automation is the process of replacing a manual step with one that happens automatically.

The benefits of autmation includes:
* Allowing people to concentrate on more complex, creative, or difficult tasks
* Consistency

However, some tasks that may require a degree of creativity or flexibility that automatic systems can't provide or for more complicated or less frequently executed tasks creating the automation may actually be more effort or cost than it's worth.

```
Let's check that this all made sense with a quick question!
What’s automation?

	* The process of telling a computer what to do
	* The process of installing traffic lights
	* The process of getting a haircut
	* [CORRECT] The process of replacing a manual step with one that happens automatically
```

### Getting Computers to Work for You
Tasks performed by a computer that need to be done multiple times with little variation are really well suited for automation.

Automation:
* Helps avoid the possibility of human errors
* Reduces the time it takes to do perfrom tasks

```
Which of the following tasks do you think are good candidates for automation? Check all that apply.

* Installing software on laptops given to new employees when they are hired
Correcto
Right on! Installing and configuring software is a task that can be automated. Ensuring that everyone gets the exact same setup and reducing the amount of manual work needed for each new employee.

* Periodically scanning the disk usage of a group of fileservers
Correcto
You nailed it! Scanning the disk usage is a task that can be easily automated. By letting the computer do it, you won't have to worry about forgetting to do it whenever it's needed.

* Investigating reports that customers are having difficulty accessing your company's external website
* Designing a configuration management system for deploying software patches
```

---

## Introduction To Python
### What is Python?
Python is a general purpose scripting language.

Benefits of using Python includes programming in Python usually feels similar to using a human language.

In programming, an interpreter is the program that reads and executes code. The Python interpreter is the program that reads what is in the recipe and translates it into instructions for your computer to follow.

### Other Languages
There are different programming languages. Also, there are platform-specific scripting languages like PowerShell which is used on Windows, and Bash which is used on Linux. Each programming languages has its advantages and disadvantages.

---

## Hello World
### Hello, World!
* Functions in Python are pieces of code that performs a unit of work
* Kewwords in PyThon are reserved words tha are used to construct instruction
* The print function in Python outputs messages to the screen.
    * The print function wraps text in quotation marks indicates that the text is considered a string, which means it's text that will be manipulated by our script.
### First Programming Concepts Cheat Sheet
* [First Programming Concepts Cheat Sheet](https://www.coursera.org/learn/python-crash-course/supplement/nonTo/first-programming-concepts-cheat-sheet)

---

## Credit
* [Coursera - Python Crash Course Week 1](https://www.coursera.org/learn/python-crash-course/home/week/1)