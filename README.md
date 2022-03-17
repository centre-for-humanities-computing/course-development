# Coding in Humanities - Course Development

This repository is a collection of ideas and an initial framework for teaching coding techniques to Humanities students. The main purpose is to be able to identify tasks that can be automated, break down those tasks into smaller ones, and solve them using programming techniques. The information proposed here is largely a guideline on how to approach these problems and set up a working plan of action to solve them. It is therefore irrelevant which programming language is used, the concepts are universal.

# Course Modules
## Technical
## 1. Basics - from the real world to the digital world
### Introduction
This module has been designed to help you understand the basic idea behind 'computational thinking' i.e. thinking in a way that helps to logically solve problems. This type of thinking is fundamental to being able to write code and solve computational problems.
### Content
How computers process instructions - peanut butter sandwich [https://www.youtube.com/watch?v=Ct-lOOUqmyY](https://www.youtube.com/watch?v=Ct-lOOUqmyY)

When a person thinks about what programming is, they often think about writing strange characters onto a black screen and seeing a waterfall of green coding snippets fill the screen - like in the movie "The Matrix". Quite disappointingly, this isn't what programming is. Programming, in a nutshell, is solving a problem then converting that solution into something a machine (computer) can understand. In fact we do programming every day, we just don't realize it. The purpose of these five modules is to provide you with the tools to convert real-world problems into computational problems then solve them using a programming language. You might be curious to know where you have been using programming in your daily life, so below is an example of that.

Imagine it's a Monday morning and you have a class starting at 09:00 at the university. You arrive at the university at 08:45 - in time to grab a cup of coffee. There are two coffee shops on campus (Coffee Shop A and Coffee Shop B) - you prefer Coffee Shop A, but the lines are usually quite long. So you tell yourself, if there are 4 or fewer people in the line at Coffee Shop A then you'll wait in line, but if there are more then you will go to Coffee Shop B. This is a very simple example of a if-statement in programming, so congratulations, you've just done some programming!

### Explanation of independence
There is no "know-all" guide to programming because each problem has a unique set of difficulties. If this weren't the case then you could just use a program someone else has already written. In many cases, you will use parts of other people's code, but the changes you make are unique to the use case you have. So, one of the most important aspects of programming is to be able to work independently and collaboratively. The independent aspect is mostly centered around being able to visualize what your solution is going to be. You need to understand the problem, develop a plan to solve it, and be able to communicate this to other people. In order to do this, you have to learn to develop an independent way of thinking.  

### Explanation of finding answers

## 2. What will the program do - thinking like a computer

### Introduction
When programming, the computer will follow your instructions 100% literally. This means that it's not uncommon for a single semi-colon or a capital letter to break the flow of a program. It is important to imagine how a computer would process the instructions you are giving it. In this way you can find errors easier and be able to fix them

Key to thinking like a programmer [https://www.youtube.com/watch?v=vrmKwQ-JPTA](https://www.youtube.com/watch?v=vrmKwQ-JPTA)

### Create expectations of what the code should do
### Identifying your own assumptions which the computer doesn't know

## Practical
## 3. Identifying real-world problems
### Introduction
**IPO tables:** 
1. **Input** - establish thinking around data types
	-	Practical: determine what your input is and what data type it is.
2.  **Processing** - establish thinking around what you expect the program to do
	-	Practical: determine what you want to do with your input.
3.  **Output** - establish thinking about what you expect to get out
	-	Practical: determine how you want you input to be at the end of the process.

### Break the problems down into smaller pieces
### Turn those pieces into control flows

## 4. Finding solutions - turning pseudocode into runnable code
### Introduction
**Finding answers to questions** 
In most cases, the answers you find to questions you are searching for will be sufficient, but not exact. Finding answers is about finding something that works similar to what you are building, then tweaking it to fit your use case. 

### Match current tech to your control flow steps
### Effective use of information gathering 
**Errors are not failures, but indications that something went wrong. They are also breadcrumbs to follow to find the solution**
**Can you reproduce the errors in isolation**

## 5. Optimizing code - producing better and more efficient solutions.
### Introduction
### Finding and following best practices
### How to know what or when to optimize

## Additional Examples Module
**Examples**
1. I am an historian and I need to go through 3000 documents to find specific people and list the sentences their names appear in. I can then read through those sentences manually to find which ones are relevant to my research.
	-  Input
	    -  	Find the data i.e. where is it located? Can you access it?
	    -   In which format is the data i.e. text files, pdfs, physical books?
    -   Processing
	    -   Read the files
	    -   Split the files into sentences
	    -   Loop through each sentence and save those which have the name to a list
    - Output
	    - Save those lists to a file which can be read or printed out
  2. I’m a linguist and I need to extract all the verbs from a document, count them and display the top 10 occurring verbs. I will use these top 10 verbs to determine what the document is about.
		- Input
			-    Find the document i.e. where is located?
			-   Determine what file type the document is.
		- Processing
			-   Read the contents of the document
			-   Separate all the words
			-   Filter out anything that is not a verb
			-   Count the remaining verbs
			-   Sort them from most frequency to least frequent
		- Output
			- Display the top 10 elements of the sorted list

# Resources

Python for Digital Humanities channel [https://www.youtube.com/playlist?list=PL2VXyKi-KpYuy_7p4nSE2z0535FDky5zA](https://www.youtube.com/playlist?list=PL2VXyKi-KpYuy_7p4nSE2z0535FDky5zA)

Problem solve like a programmer [https://www.youtube.com/watch?v=x77-gT8bWLo](https://www.youtube.com/watch?v=x77-gT8bWLo)
