---
title: "NA"
status: "NA"
order: NA
---

# Modern Javascript Course 2023 by Teddy Smith

#### The ultimate guide to *Modern Javascript Course 2023* 

//This is a summary of Javascript explained in my own words

> *The first principle is that you must not fool yourself and your the easiest person to fool)*

## Resources

Here are some links you might find helpful!

* **youtube paylist** -> https://www.youtube.com/watch?v=36Evo9c8gfU&list=PL82C6-O4XrHeQQPw8J8-f2XHuXsuMFc-T

## Table of Contents


Template

- Notes
- Teen
- Kid

## Intro + VSCode Setup
## External File + Chrome Dev Tools
## Let vs Const vs Var

Modern JavaScript 2023 - 3. Let vs. Const vs. Var - YouTube
https://www.youtube.com/watch?v=xmXEb9FF894

What is a variable & memory reference? (5 year old)


- Variables are used to remember stuff


- A variable is like a toy and the computer is the genie who stores all your favourite toys. By placing your toy with your genie, it knows where to store it. If you want to play with toy, your have the ask for it from Mr Genie. However there are rules for genie. 

1.If you put a red sticker on your toy, the genie knows the toy can be cloned or changed it into a different toy. `Let`

2.If you put a blue sticker on your toy, the genie knows the toy can ONLY be cloned.

You want to hear something interesting? 
When you ask for the toy back, you know the name of the toy.

When you give Mr Genie the toy, he doesn't see what you see. He sees as a combination of jewellery, gold, watches, coins! For him to go get it from magical storage, he'll have to get the exact same combination.


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
## Data Types
Modern JavaScript 2023 - 4. Data Types - YouTube
https://www.youtube.com/watch?v=gEOYb0LHuS0

Transcript:
(00:00) so as I mentioned in my previous video computers are simple computers can only store data and they can only manipulate data but there's a caveat to this computer store and manipulate data in different ways depending on the data type and it kind of makes sense if you store a number you don't want numbers to behave like words you don't want something that's not there to behave like something that it that is there and in this video I'm going to break down each and every single data type so that
(00:35) you have a really good in-depth understanding so that you know what's going on and you know how the computers actually storing these a lot of this stuff is very complex at first but if you don't understand what it is just try to make it through the video so our first data type is going to be the good old number no secret there a number is a number and the great thing about JavaScript is that you don't need to be precise with your numbers you don't need to tell JavaScript that it is a decimal
(01:05) number you don't need to tell JavaScript it is a integer number JavaScript is going to do all of the work for you the only thing that you really need to be concerned about is that it is a number but there is a lot more to it than that there is also this word called A Primitive A Primitive is an important word because a number is stored on the stack now this is Advanced I will admit but it's good to be introduced to these early because this will help you a lot in your career so let's just go ahead
(01:37) and let's just test out how do we actually create numbers what is the process to actually create a number there is no secret on how to create a number all you have to do is declare your let and then we will give a number another funny example of rats let's just say we're going to declare a variable of the number of rats in New York City and if you Google this number there are approximately according to google there are 2 million rats in New York City that seems kind of low to me but let's just
(02:06) kind of roll with it for a second so the number is going to be 2 million there are no commas in it you just put it there and let's just say you want to say maybe there's a rat got chopped in half somewhere and you need a half rat there uh JavaScript is going to do the exact same thing you do not need to distinguish between a decimal don't put any type of comma in there just go ahead throw that number in there javascript's going to do all of the work you don't even have to worry about it but just
(02:37) remember if you feel so inclined you could put a decimal in there it does not matter JavaScript is not going to complain like other languages like c-sharp and Java so our next data type is going to be the string a string is kind of a funny word when I first heard the word string it didn't really make any sense because there's no connection between what a string is in programming and what a string is in real life but really what a string is at the end of the day it's just a word and we have these things called strings because if
(03:13) you were to just go into uh JavaScript like this and you don't need to type this out just yet but if I were to say the number of rats was equal to 2 million just like this you would get an error and you get an error simply because the computer at the end of the day is powerful but it's kind of dumb at the same time too because it doesn't know exactly what you want you need to be more explicit and the way that you be more explicit is very simple you say so let's just say our favorite what's your
(03:44) favorite type of rat just put your favorite type of rat in this actual variable so let's go into a variable and my favorite type of rat is going to be a wolf rat it's the biggest rat it's the most badass it's the scariest my favorite type but you could also have a fancy rat if you want to if you just want something a little bit more cute but I'm gonna go with a wolf rat and if you look right here the only thing that I did was put quotations and these quotations tell the tell the computer
(04:14) that this is indeed a string and if we go down here we can do all types of cool things we can even make our own story about rats let's just say yesterday on the subway yesterday on the the subway I was bitten by a and then I closed out the parentheses right here so this is also a string two even though it's not initialized by a variable we don't have to put strings in variables and then I go into here and I say I was bitten by my favorite type of rat which is a wolf rat and then I'm going to go over here pull out my
(04:55) console and then what what happens is I go into here and I get a cool little story with my strength yesterday on the subway I was bitten by a woof rat and really at the end of the day that's all there is to know about strings but let's also talk about is a string a primitive data type or is a string another type of data type and I haven't explained to you the other type of data type so just realize that in JavaScript strings are a little weird something about some the people down at JavaScript got a little
(05:27) crazy one day and they actually turned a string into a primitive data type so if a string is one of the simplest data types that you can possibly have it isn't it it is indeed a primitive data type so on to booleans booleans are another topic that have been totally over complicated and programming and you don't need to know anything there are sign there's a whole realm of science dedicated to bullions but you don't need to know any of that the only thing that you need to know to be a professional
(05:59) software developer is that there is a true and there is a false that is really all that a bullion is and once again it is a primitive data type and that's all it is it's just a true or false but why would we even need a true or false what is the reason why did we even create booleans to be honest with you I have no idea but what I think really happened was that people used to just have strings back in the day so uh is Rhett cute and wolf rats are not cute so obviously that's going to be false but
(06:34) today we have a false and as you notice there are no quotations there's no quotations around it and what I think happened was people just would do this back in the day and eventually people realize that this is not the best way to do things so they're just like well we'll just create our own primitive data type we'll just call it false and it works way better that way and that's all that it really is it's just a toggle a lot of times they use them to toggle buttons and anything that can be on or off is going to be
(07:07) something that you would use for a Boolean that's all that it is so next up is going to be null and null can be a real brain Buster to kind of wrap your head around and essentially null is nothing at the end of the day it's kind of one of those philosophical things to think about and the best way that I could possibly describe what null is is with a really good real example let's just say you did some type of query on a database and that database turned nothing what you would likely get back inside of your program or what the
(07:43) computer would actually turn this nothing into from this database would be a null and a null at the end of the day really just signifies nothing and you can easily make a null although I don't know why you would do this this doesn't really make sense and you will understand null more as you become a better software developer but just right as of right now you don't need to know a lot about how null actually works just know that null is nothing things can also get complicated because we all we also have this thing called undefined
(08:19) and undefined is another Brain Buster trying to distinguish between null and undefined is a total can throw you in a total Loop but let me explain it to you like this null is signifies that you intend for something to be known undefined is almost like it doesn't exist think about it like he's saying if a tree falls in the woods does anybody hear it type of thing it just literally does not exist let's create a situation when you would see undefined and the most common way that you'll probably see
(08:57) undefined is when you actually declare something but you don't initialize it and I'm going to add a little note up here so there's a big difference between a declaration and instantiation a declaration basically means you declare something but you don't actually put anything inside of the value so if I went here and I declared far just rat that is totally valid and watch what happens when I actually try to console log this into the browser and you don't have to do this if you don't want to but
(09:32) if you do want to feel free to this is when we get undefined so it's there but there's nothing inside of it we haven't initialized a null null is we we actually put nothing into is nothing a varat means there's actually nothing there we didn't initialize anything we didn't actually put anything inside of the value it's it exists but at the same time it doesn't exist and if that's really confusing I'm sorry but that's probably the best way that I can explain it and I hope that did it but if it
(10:04) didn't it's okay it will make sense as you go further along in your career so the last data type and probably one of the most important is going to be the almighty object the object is likely one of the most powerful paradigms in programming an object is one of the unsung heroes that people don't really talk about people talk about AI people talk about algorithms but the object is like the unsung hero of programming because it is so powerful and the best way that I could describe an object is like this it's pretty much a baby Excel
(10:41) spreadsheet of data in an Excel spreadsheet you have rows of data you can keep track of different dates and you can keep all of your data and one you know contained place and an object is the same exact thing in programming but it's just in a small self-contained variable it's pretty much taking a baby Excel spreadsheet jamming it in a variable and now you have a nice little Excel spreadsheet floating all around your program that you can use in different places and you bundle all of your strings and your numbers and your
(11:11) bullying in your nose into one giant object and then just Jam them inside of an object and that's basically a really crude way of describing what an object is so let's declare an object or let's initialize and let's declare and initialize an object in vs code so first thing that we want to do is I'm just going to go down here and the first thing I'm going to declare some wrap properties we are going to make a specific object for our apps because we want to put all of our variables that we declared up here into
(11:47) our actual object here so that we can keep better track of them so I will say number of rats in New York is equal to 2 million I don't know if that's 2 million or not then we put a comma and then we go down here and we do the exact same thing so favorite type of rat is Wolf rat so we have wolf rat then here we'll just have our Boolean and we'll say is rat cute of course uh false because wolf rats are not cute okay so what we want to do here is let's go ahead and console lock it and this isn't going to be rocket science guys
(12:31) this is kind of simple stuff let's just see what this actually looks like in our browser so that we can we can actually see what this little baby Excel spreadsheet this weird dude on YouTube is always talking about so this is exactly what it is and instead of having all of our variables floating around we could just go ahead and delete these and we could have all of our properties stored inside of an actual property instead of having to just have all of our prop instead of having all of our variables floating
(13:01) around and causing all types of Chaos in our program and that is pretty much it for the data types as of yet there's more going on down the line but for right now let's not get too carried away and let's just stick to the basics anyways I hope that you guys enjoyed this if you did make sure to smash that like button smash that subscribe button and as always thank you for watching
## Strings In-Depth
## String Methods
## String Escapes + Template
## Arrays
## Slice vs Splice Explained
## Comparison Operator (=== vs ==)
## If Else Statements
## Logical Operators (&&, ||)
## Objects Explained Simply
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

> *Array destructing is a easier way of grabbing variables from the array and reusing them how you like.

Imagine getting food from the fridge. 

An inexperience human would grab a item close the fridge door and put it onto your plate/array and repeat until you have all your items. This can be bothersome and inefficient.

An experienced human would have a list prepared. Then grabw all the items corresponding to the list and place it on the plate/array. This can be more efficient and there's less prone for forgetting an item.
 )*

This is one way of picking individual items from an array.

>const refrigerator = [ 'chicken breast', 'broccoli", 'potato' ];

const chickenBreast = refrigerator[0];
const broccoli = refrigerator[1];)

- On a larger scale this can lead to typos, mistakes and lot more lines of code.

However with *Array Destructing* 

> const [chickenBreast, broccoli] = refrigator;

Console.log(chickenBreast, broccoli) = chickenBreast + broccoli;)

- It looks more condensed.
- Left of the statement is where you storage the variable names. Note ==THE ORDER MATTERS==

More exampples

Let a, b;
[a, b] = [10, 20];

Console Log(a,b) -> a = 10, b = 20;


