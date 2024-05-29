---
title: "NA"
status: "NA"
order: NA
---

# Modern Javascript Course 2023 by Teddy Smith

#### The ultimate guide to _Modern Javascript Course 2023_

//This is a summary of Javascript explained in my own words

> _The first principle is that you must not fool yourself and your the easiest person to fool)_

## Resources

Here are some links you might find helpful!

- **youtube paylist** -> https://www.youtube.com/watch?v=36Evo9c8gfU&list=PL82C6-O4XrHeQQPw8J8-f2XHuXsuMFc-T

## Table of Contents

Template

- Notes
- Teen
- Kid

## Intro + VSCode Setup

## External File + Chrome Dev Tools

## Let vs Const vs Var X

<!-- ADD IN THE TDLR SUMMARY -->

Modern JavaScript 2023 - 3. Let vs. Const vs. Var - YouTube
https://www.youtube.com/watch?v=xmXEb9FF894

What is a variable & memory reference? (5 year old)

- Variables are used to remember stuff

- A variable is like a toy and the computer is the genie who stores all your favourite toys. By placing your toy with your genie, it knows where to store it. If you want to play with toy, your have the ask for it from Mr Genie. However there are rules for genie.

  1.If you put a blue sticker on your toy, the genie knows the toy can be cloned or changed it into a different toy. `Let`

  2.If you put a red sticker on your toy, the genie knows the toy can ONLY be cloned. `Const`

You want to hear something interesting?
When you ask for the toy back, you say the toy's name.

When you give Mr Genie the toy, he doesn't see what you see. He sees as a combination of gold coins! For him to go get it from magical storage, he'll have to get the exact same combination of gold coins.

What is a variable? (10 year old)

Transcript:
(00:00) so this video we are going to be talking about variables in JavaScript variables are the smallest most fundamental building blocks of software they are the subatomic particles of software and if I could give anybody an abstraction or a way of Simply describing what software development is it is basically when you are developing software you are creating the most flexible the most powerful Excel spreadsheets on the planet and I say that because there's not really much you can do with software you can create
(00:39) data you can read data you can update data you can delete data those are that's the acronym crud crud and Excel spreadsheets are the same thing but in Excel spreadsheets you are self-contained you can't just do whatever you want to in **Excel spreadsheets and a variable is going to be one cell and the Excel spreadsheet and this fits perfectly because computer memory almost functions like an Excel spreadsheet there are specific places in memory and when you create a variable or when you assign a variable** which we will
(01:16) do here in a second **all that you are doing is you are placing a place in memory logically and you are doing it in a way that's very readable to the human mind** so if you don't really understand what's going on as of yet let's just go and let's give a couple examples here in vs code so what I'm going to do is I'm going to go ahead I'm going to get rid of all this up here because we don't really need this anymore and what we're going to do is we're going to create a
(01:44) funny story about rats or your favorite animal I'm gonna create a story a funny story about rats I'm going to assign some variables and we're going to have a little fun here so if you want to copy mine that's okay but if you want to follow along and create a story about rats just follow along okay so what I'm gonna do is I'm going to create this Let rat equal to and I'm going to say we are going to assign a variable to this is going to be a radioactive rat we are going to tell a story about radioactive
(02:19) rats in the New York City subway so we're going to say radioactive subway rat so when we actually assign this variable what's going to happen is that let is going to say that we can actually change this variable if we want to and this rat word is going to be a logical representation almost as if you are assigning a value to an Excel spreadsheet cell and you could just assign this variable to the actual specific place of memory that would be like a hex code that would look something like this but we call it just
(02:57) words like this because we need words as humans because we need to be able to keep track of it and when we actually assign this word here the string as we would call it to this variable what it's doing is it's basically **assigning this word to a place in memory** but this is kind of you know why would we actually do this well first you need to do this because you need to be able to **keep track of stuff** and number two you want to be able to **reuse** this variable in other parts of your software so what I'm going
(03:30) to do is I'm going to go down here I'm going to console log This and like I said we're going to create a funny story and I'm going to say yesterday on the subway in NYC I Was Bitten by a give it a space and then we are going to place our rat variable within our console log and what's going to happen is that it's not going to log it right now because our server has actually shut down so what you want to do you either want to right click and open with live server or you want to go down here and hit this button right here
(04:09) I like to hit this button because it it's just easier and it's just like a graphical interface and we are going to console log this so let's go ahead and let's console log it and when I click the refresh button we get a funny story yesterday on the subway in New York City I was bitten by a radioactive subway rat but it's important to understand because we have this **let keyword right here we can actually reassign** this so let's just say we get halfway through our story and we want to assign it maybe you are not
(04:45) bitten by a radioactive subway rat maybe you are bitten by a giant wolf rat and we'll give it caps lock just to kind of be funny but let's just say you want to change your rat to a giant wolf rat and instead of getting bitten by a radioactive subway rat you are bitten by a giant wolf rat and that demonstrates **how variables can be assigned to memory and they can also be changed in memory another thing that will happen is that you will see this word called const const is essentially let but you cannot change it that is the only difference between the two** so if I have the const up here and then I go up here and I assign rats and I give it uh wolf rat right here this is perfectly valid we will be bitten by a woof rat but watch what happens when I actually try to reassign this to fancy rat fancy rat so maybe let's just say we don't see wolf rats anymore we only see fancy Rats Watch What Happens when I try to change it you get this error that says assignment to constant variable uncut you get a type error and that's because this is const
(06:10) this is a constant variable it cannot change and we have that because in certain circumstances you don't want your variable to change maybe a little confusing at first but this is something that we will talk about down the line the other variable type that you will actually see is the bar so VAR rat and this is going to be woof rat just like this so what we assign it the wolf rat and I need to give it a semicolon and what happens is it's the same exact thing as let but it has something called block scoping now block scoping is going
(06:51) to be way too confusing right now that's something that we're going to have to talk about down the line I don't want to confuse you guys too much but just realize that you don't want to use VAR anymore there are some circumstances when you may want to use far but overall the whole entire JavaScript Community has made it so that or has decided that bar is no longer what people are going to use from now on you want to use let or you want to use const you never want to use VAR and if you use for it may
(07:29) make you look stupid in front of other people so just don't use R anymore so one last thing before this video is over let's talk about how you actually leave comments Now comments are great because they help people learn it's essentially a great way to keep notes for yourself it's a great way to be able to document your code and you're going to see comments everywhere now there's many different ways that you can turn stuff into comments but the best way to create a comment is to just press Ctrl slash
(08:06) and it will do all of the commenting for you so if you want to comment something just press Ctrl slash and if you are on a Mac you want to press command slash so Mac it is command slash if you are on a PC it is control slash you could and go in manually and do the double slashes just like this but I typically recommend just taking the easy way a lot of times in programming it's best just to take the easy way and just go ahead and press that Ctrl or command slash just like this and it will help you a ton it will
(08:42) save you a bunch of time and it will allow you to create great notes for yourself while you are learning so be let maybe use just say this is the best way right here and it's going to give you a bunch of squiggly lines because this is not a string so in order to make it so that this is actually nodes Ctrl slash right here and that is how you create comments anyway that's going to be the video for today I hope that you guys enjoyed this if you did make sure to smash that like button make sure to smash that subscribe button and as
(09:14) always thank you for watching

## Data Types X


**1. Numbers:**

* In JavaScript, numbers can be whole numbers (integers) like 42 or -100, or they can have decimals like 3.14 or -9.81.
* JavaScript is flexible and can handle both types automatically. You don't need to declare a number as an integer or a decimal beforehand.

**2. Strings:**

* Strings are used to store text data. They are created by wrapping the text in quotation marks, either single ('like this') or double ("like this too").
* Strings can hold letters, numbers, symbols, spaces, or even emojis!

**3. Booleans:**

* Booleans are used to represent logical values. There are only two possible values for a boolean: true or false.
* They are often used in conditional statements to control the flow of your program based on whether a condition is true or false.

**4. Primitive vs Non-primitive data types:**

* **Primitive data types** are simple building blocks of data. They hold a single value and are stored directly in memory. In JavaScript, these include:
    * Numbers (as discussed earlier)
    * Strings (text data)
    * Booleans (true or false)
    * null (represents the intentional absence of a value)
    * undefined (represents a variable declared but not assigned a value)
* **Non-primitive data types** are more complex data structures that can hold collections of other data. They are referenced by memory location instead of storing the value directly. In JavaScript, objects are the most common non-primitive data type.

**5. null:**

* The `null` value represents the intentional absence of a value. It's like saying there's no data there on purpose.

**6. undefined:**

* The `undefined` value indicates that a variable has been declared but hasn't been assigned a value yet. It's like saying the variable exists, but it's empty.

**7. Objects:**

* Objects are the most powerful data structure in JavaScript. They are used to store collections of data in a more organized way.
* Imagine a mini spreadsheet with rows and columns. An object is like that spreadsheet, but instead of referencing cells by their position, you use unique keys (like names) to access specific pieces of data (like values). 
* Objects can hold different data types within them, including strings, numbers, booleans, and even other objects! This allows you to create complex data structures to model real-world things.

Modern JavaScript 2023 - 4. Data Types - YouTube
https://www.youtube.com/watch?v=gEOYb0LHuS0


## Strings In-Depth

## String Methods

## String Escapes + Template

## Arrays

- An array is like a basketball rack. As a all year round pro you will need to play with different kinds of balls such as FIBA, Molten, Wilson, Spalding. In order to store these balls neatly in your house, you put them in the basketball rack in your favourite order from left to right. The first ball's position is 0. If you want to use a specific

Arrays are like boxes that hold things, but with a twist:

Reference Type: Imagine you have a label with the box's location. When you give someone the label, they can access the box's contents. Arrays store a reference, like a label, to the actual data they hold, not the data itself.

Mutable Elements, Immutable Array: The things inside the box (the data in the array) can be changed. You can take things out or put things in. However, the box itself (the array) cannot be resized or change its location in memory. It's like having a fixed number of slots you can fill with different things.

So, arrays are like labeled boxes where you can change what's inside but not the box itself.

## Slice vs Splice Explained

## Comparison Operator (=== vs ==)

## If Else Statements

## Logical Operators (&&, ||)

## Objects Explained Simply

> Objects is the real MVP and I say that because it's one of the most powerful data structures that you will ever use and its power comes from the ability to quickly bundle all of your data together almost like a briefcase or an excel spread sheets. Objects have these things called properties where you can quickly input dates you can quickly input strings and you can even add things like arrays in other objects)

Why choose objects over arrays?

You'd generally use objects over arrays when your data represents a single entity with various properties, rather than a simple collection of similar items. Here's why objects might be a better choice:

_Meaningful Properties_: Objects allow you to define named properties for your data. This makes the code much more readable and understandable compared to arrays where elements are accessed by numerical indexes (0, 1, 2...). For example, instead of ["Alice", 30, "London"], you could have { name: "Alice", age: 30, city: "London"}.

_Data Flexibility_: Objects can hold different data types within their properties. You can have strings, numbers, booleans, arrays, or even other objects nested within them. This flexibility allows you to model complex real-world entities effectively.

_Direct Access_: Accessing data by property name with dot notation (.) is generally faster and more convenient than using numerical indexes in arrays. This makes your code more efficient, especially when working with many properties.

_No Order Constraint_: The order of properties in an object doesn't necessarily matter (although in some situations it might). This is useful when the order doesn't have any significance for your data.

However, arrays are still irreplaceable when you have a collection of similar items where order is important. For instance, a shopping list or a sequence of instructions would be better represented as arrays.

In summary, use objects to represent entities with various properties, and use arrays for ordered collections of similar data items.


## Stack & Heap Explained (Value & Reference Types)

## For Loops

## Nested Loops

## For-Of & For-in Loops

## Functions

## Parameters + Return

## VSCode Debuggings

## Understanding Scopes

## Arrow Functions & 'this' Explained Simply

## 'this' explained Simply (Further)

## Higher Order Functions

## Hoisting

## ForEach

## Array Map

## Rest and Spread

## Destructing

> \*Array destructing is a easier way of grabbing variables from the array and reusing them how you like.

Imagine getting food from the fridge.

An inexperience human would grab a item close the fridge door and put it onto your plate/array and think what other item should I grab. This can be bothersome and inefficient.

An experienced human would have a list prepared. Then grab all the items corresponding to the list and place it on the plate/array. This can be more efficient and there's less prone for forgetting an item.
)\*

This is one way of picking individual items from an array.

> const refrigerator = [ 'chicken breast', 'broccoli", 'potato' ];
> const chickenBreast = refrigerator[0];
> const broccoli = refrigerator[1];)

- On a larger scale this can lead to typos, mistakes and lot more lines of code.

However with _Array Destructing_

> const [chickenBreast, broccoli] = refrigator;
> Console.log(chickenBreast, broccoli) = chickenBreast + broccoli;)

- It looks more condensed.
- Left of the statement is where you storage the variable names. Note ==THE ORDER MATTERS==

More exampples

Let a, b;
[a, b] = [10, 20];

Console Log(a,b) -> a = 10, b = 20;
