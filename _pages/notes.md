---
layout: page
title: CSA Notes
permalink: /notes/
---

# Unit 1: Primitives

## Vocab
- markdown: text to HTML conversion
- int: integer, any whole number
- double: tens place in decimal
- string: words
- boolean: true/false
- primitive: data types already defined in Java

## Notes
_notebooks:
- mostly jupyter files
- building block of markdown, python, java, javascript into a jupyter notebook. 

_posts: 
- markdown .md files
- frontend web design with markdown, html, and javascript

_word
- word .docx files
- save Microsoft or Google documents into a docx format

Homepage
- sourced by the index.html file
- personalize and customize your Fastpages home page
- standard name for your web sites landing page.

## Assignments
[TT 1.0 Tools and Equipment](https://iriisyang.github.io/Iris-Yang/markdown/2022/08/21/FirstPost.html)

[TT 1.1 Innovations Week 1](https://iriisyang.github.io/Iris-Yang/techtalks/2022/08/29/TT2.html)

[Student Lesson 1](https://iriisyang.github.io/Iris-Yang/java/2022/10/15/Primitive.html)

# Unit 2: Using Objects

## Vocab
- object: member of a java class
    - has identity, state, behavior
    - declaration, instantiation, initialization

## Notes
Console Based Menu
- import java.util.Scanner; //library for user input
- import java.lang.Math; //library for random numbers
- public final String[][] COLORS = { // 2D Array of ANSI Terminal Colors
    - columns and rows [][]
- within terminal
- looks like list with different options and uses user input

GUI Menu
- separate program that opens up menu
- more user friendly
- very visual display

Code.org
- method format "variableName.methodName();"
- uses painter as a visual object

Class Defined
- public class classname
- class to add variables, objects, etc

New Instance of Class
- new Menu();
- create an object of class

Calling a Method
- action needs to be performed

Object Mutating Data
- change in original state of input
-  for (int i=0; i<nums.length; i++) {
            sum +=nums[i];
        }

## Assignments

[TT 1.2 Innovations Week 1](https://iriisyang.github.io/Iris-Yang/techtalks/2022/09/05/TT3.html)

[Student Lesson 2](https://iriisyang.github.io/Iris-Yang/java/2022/10/16/Objects.html)

# Unit 3: Boolean Expressions and if Statements

## Notes
- if statements: executes code if parameters are true
- if/else: executes code if parameters true, otherwise executes code within else statement
- switch code: quicker and more efficient for more code and conditions
- demorgan's law: logic using and (&&) and or (||)

## Assignmnets

[TT 1.3 Backend Development](https://iriisyang.github.io/Iris-Yang/techtalks/2022/09/11/TT4.html)

[Student Lesson 3](https://sarayu-pr11.github.io/teamGrapeSnails/java/jupyter/2022/10/17/IFsLesson.html)

# Unit 4: Iteration

## Notes
Iterations
- make code shorter - simplify repeating code into simpler section

While Loop
- while a condition is met, code will keep
- do while loop - execute not matter what

For Loop
- for as long as a condition is true, continue printing

Recursion Loop
- own function that repeats over and over again

Nested Iteration
- not a official loop
- put loop inside loop - can use any of the pervious loops

## Assignmnets

[TT 1.4 Backend Development](https://iriisyang.github.io/Iris-Yang/techtalks/2022/09/20/TT5.html)

[Student Lesson 4](https://iriisyang.github.io/Iris-Yang/java/2022/10/19/Iterations.html)

# Unit 5: Writing Classes

Classes
- classes are "blueprints" that we use to instantiate objects
- classes are an essential aspect of OOP

Anatomy
- Object
    - state, attributes, behavior
    - represented by an instance in the program
- Class
    - defines an abstract data type
    - object references: string variable
    - instance variables: attributes, behaviors, data for objects

Functions
- methods: the action or behavior of an object
- constructor: special method for object instantiation, sets the initial values for variables, default constructors have no arguments
- main: tests the class
- accesser: accesses the values of variables, returns a copy of the variable
- mutator: changes values of variables

Writing Methods
- method_definition(Modifiers, Return Type)
- method_signature(Name, Parameters)
- method_body(Code)
- "Object.method()"

## Assignments

[TT 1.5 Design Starters](https://iriisyang.github.io/Iris-Yang/techtalks/2022/09/25/TT6.html)

[Student Lesson 5](https://iriisyang.github.io/Iris-Yang/collegeboard/2022/10/22/WritingObjects.html)

# Unit 6: Array

## Notes

- contains a collection of data
- can be primitive or referenced
- element - one value in an array
- index - the position of one value in an array
- use loop to traverse through array

## Assignments

[TT 1.6 Project Approval](https://iriisyang.github.io/Iris-Yang/techtalks/2022/10/04/TT7.html)

[Student Lesson 6](https://iriisyang.github.io/Iris-Yang/collegeboard/2022/10/22/WritingObjects.html)

# Unit 7: ArrayList

## Notes

add(int index, element)
- adds an element to the list

addAll(int index, Collection collection)
- adds all the elements in a list to another

size()
- outputs the size of a list (number of elements)

clear()
- clears everything in a list
- reference list is stored

remove(int index)
- removes the element from a list with that specific index
- shifts the rest of the elements to the left and decreases their index by 1

remove(element)
- remove the element with a specific name

get(int index)
- obtains the element of that index

set(int index, element)
- replaces what is in that index with the new element

IndexOf(element)
- returns the index of that element

lastIndexOf(element)
- returns last occurrence of an object if not present in list

equals(element)
- true or false if two objects (lists) are equal to one another

hashCode()
- returns the hashcode of a list

isEmpty()
- true or false if the list is empty (has no elements within)

contains(element) 
- returns true if the list contains the element

containsAll(Collection collection)
- returns yes if the list contains all the elements of the other list

sort(Comparator comp)
- sorts elements

## Assignments

[TT 1.7 Project Approval](https://iriisyang.github.io/Iris-Yang/techtalks/2022/10/09/TT8.html)

# Unit 8: 2D Array

** need more review

# Unit 9: Inheritance

# Unit 10: Recursion

** need more review

# PBL Notes

AWS Deployment (linux)
- "ps" linux command gives info related to process of system
POJO
- plain old java object
- interact with backend code through frontend (more straightforward)

# Trimester 1 Reflection

I came into this class with little expectations. I had a little bit of computer science background from doing Cyber Patriot in the past, but not really much coding other than a few summer camps and classes here and there when I was younger. I really liked the emphasis on a collaborative environment in this class was really enjoyable compared to the cutthroat environment in that club. I also enjoyed the emphasis on project based learning in this class. It is really useful for the real world and more interesting that just doing practice college board problems. I did struggle a lot in this class, especially in the beginning. Especially, with little background, I did not really know where to go with a lot of the assignments. I was able to rely a lot on my group and their guidance to help me. Their help was key to my success in this class. After getting the hang of the class, it was easier. However, I still have much to learn and more to improve on and I hope that I can help my group more on future projects in coming trimesters.