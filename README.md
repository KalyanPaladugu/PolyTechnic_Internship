# PolyTechnic_Internship


## Task:Develop web application(Frontend(HTML5,Css3,Bootstrap))

### At Least 2 web pages for Application
 + HTML5
      - Tables
      - Forms
      - Colors(Html color codes)
      - Images
      - Marquee
      - List
      - Iframes
      - Video
      - Audio
      - Navigation
      - Nav Elements
      - Dropdowns
 + CSS3
      - Selectors
      - Flexbox
      - Grid view
      - Media queries
      - Padding & Margin

 + Bootstrap4
      - Color codes
      - Grid system
      - Tables
      - Modal
      - Cards
      - Carousel
      - Tooltips & Popover
      - Forms
      - Nav components

25-8-2020

# JavaScript

+ JavaScript is a text-based programming language used both on the client-side and servrside that allows you to make webpages interactive

## History of JS
+ Brendan Eich was introduced the JavaScript (in 1995)
+ Initially we called it as a LiveScript
+ For implementing the dynamic behaviour of website
+ JavaScript is an interpreter language
+ To implement high end JS Modules, We have to focus on ES-6

### Datatypes

+  Number
+  String
+  Boolean
+  Object
+  Function
+  Null
+  Undefined
+  Array

### Convertion functions


+ Number()
+ parseInt()
+ parseFloat()


### JavaScript Alerts
 + There are 3 types of popupbox are available in JS
      - alert()
      - prompt()
      - confirm()
 
 
### console statements

+ console.log()
+ console.info()
+ console.warn()
+ console.error()


# Functions
+ Functions with out parameters
+ Functions with- parameters

## JS Events

+ onclick
+ onmouseover
+ onmouseout

26-8-2020:
============
# ES 6 Features

+ let, const
+ var,let,const
  - Scope
    - Functional or block 
  - Redeclare
  - Redefine

### var
  
+ Function level scope
+ var variable can be Redeclared
+ var variable can be Redefined


### let
+ Scope is block level
+ let variable can't be Redeclare
+ let variable can be Redefined



### const
+ scope is block level
+ const variable can't be Redeclare
+ const variable can't be Redefine

# Regular Expressions

+ Regular expressions are mainly used to match patterns
+ Regular expression is an object that describes a pattern of characters

Syntax:
    /pattern/modifiers
   
   

### Modifiers:
+ g  for global matching 
+ i  for case-insensitive matching
+ m   multiline matching  (^ for first character matching $ for last character matching)

#### Brackets

+ brackets are used to find the range of characters

[abc]   - fist character of your input should contain any character in list of bracket
[^abc]  - Find any character not between the brackets
[0-9]   - find any character between 0 to 9 digits
[^0-9]  - to match any non digit
(firstpatter | second pattern)  - to include no of patterns for input


#### Quantifiers

+ n{input range}  Matches any string that contains a range  ( n is may character or digit)
+ n{4,}           Matches input contain atleast 4 characters


Task:
======
- First two characters are digits
- from third character onwards it contains atleast 3 letters
- any one special character
- any digits

Tasks:
=======
Patterns for mobile number ,Email
   - Mobile Number
   ```
    ^[6-9][0-9]{9}      ^[6-9]+\d{9}
   ```
  -Email Id
  ```
  ^\S+@+\S+.\S+
  ```
   
  
 
27-8-2020:
===========

+ Develop a Regular expression for the  password
  - One capital letter
  - One small letter
  - One digit
  - One special character
  - Password length is between 8 to 16 characters

```
^(?=.*[!@#$%^&*])(?=.*[A-Z])(?=.*[a-z])(?=.*[0-9]).{8,16}$
```

01-09-2020:
===========

Promises:A promise is an object that may produce a single value some time in the future.Promises are used to handle asynchronous operations in JavaScript.
Prior to promises events and callback functions were used but they had limited functionalities and created unmanageable code

A Promise has four states:
- fulfilled: Action related to if the promise succeeded
- rejected: Action related to if the promise failed
- pending: Promise is still pending example: not fulfilled or rejected yet
- settled: The Promise has fulfilled or rejected


      
      
 ### Benefits of using Promises:
 
+ A promise can Improves Code Readability
+ For Better handling of asynchronous operations
+ In asynchronous logic, it has a better flow of control definition
+ For Better Error Handling
    
    
Examples:
===========
- Fetch API
- Cache API
