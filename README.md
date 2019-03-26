# JavaScript assignment

## Some useful resources
* Some [JavaScript tutorials](https://www.htmldog.com/guides/javascript/)
* The complicated [resources in the You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) series, including [your reading last week](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch2.md)
* [A resource for CSS/style/colors](https://htmlcolorcodes.com/)  
* [An excerpt from a specific workshop site](https://witny-summer-guild-2018.github.io/day_4_exercise_2.html) (for a different audience than yourselves) which addresses some common questions about jQuery
* [The simple JSFiddle example from class](https://jsfiddle.net/2of65j8q/)
* A [W3Schools resource on JavaScript output](https://www.w3schools.com/js/js_output.asp)
* Google, Piazza, your classmates, office hours, lab time!

## Included files
* This `README.md`, which you should edit with answers to the questions
* `jsPracticeLab.html`, which you'll need to edit and try out
* `jquerylib_submit_example.html`, which you'll need to edit and try out

## Your goals for this lab

### Broadly
The aim for this lab is to practice adapting to and understanding code in a new-to-you (or not) language and its own libraries/packages -- JavaScript, in this case.

The programming skills you have built up till now are useful for *Python programming*, but, more than that, they extend to fundamentals of many kinds of programming.

This experience is *not in any way* about becoming an expert JavaScript programmer. Instead, it is about using what you *do* have experience with -- and your skills in *learning new things* that relate to programming -- in order to make educated judgments about some brand new-to-you code, even if you haven't learned in detail about it yet. That's part of what being in technology -- or even technology-adjacent -- will often mean.

### Specifically

Below are a bunch of questions and indications of things to do. For each indication of something to do with code, there is also an accompanying question to answer or brief explanation to give.

**To complete and submit this assignment, you should:**

* Fork (and clone) this repository ############# DONE
* Add our instructional team as a collaborator to your fork (see instructions for adding collaborators on Canvas)  ######### DONE
* Edit this `README.md` file with answers to the questions/prompts, briefly, using Markdown formatting so that the questions appear in bulletpoints and the answers appear clearly below each respective question, *not* as bulletpoints.
* Add all names of those who worked on this (as indicated below)
* Make the changes that are indicated below to each of the `.html` files with JavaScript programs provided. (You'll probably do this concurrently with answering questions)
* Commit (as you go) and push your changes to all three files to your GitHub forked repository.
* Submit a link to your repository on Canvas. (This HW doesn't have an autograder -- it will be graded by hand/by humans this time.)

### Important notes
* You are *more than* welcome to work together on this, but **you must <u>each</u> submit a repo to be graded on it**, so if you do work together, you should do the following:
	* Make sure each one of you understands all the work -- YOU are responsible for using and knowing this information
	* Write each person's name & uniqname who worked on the assignment together on your submitted `README.md` file (you'll see a space for this below)

* In answering questions, please make sure the formatting is clear to read and that you have updated the names of everyone who worked with you, with your name first (see below).

* In answering questions, assume all of the questions include a *explain briefly* note -- you do NOT have to, and should not, write extended paragraphs. Be as concise as you can and explain in your own words. Don't worry about "whether it's enough" -- just worry about conveying your understanding so you can read it later, or even give it to someone else, and the answers will help/make sense.

* It is not acceptable to copy and paste answers from the internet and submit them as your own. If you cite things, make sure you provide a citation, including to links. If you get information from a resource and rephrase it so you're basically explaining an idea, that's just fine for an explanatory purpose in this assignment, but you *must* cite any quotes or examples that aren't yours.

* **For grading:** we are grading on...
	* Following the instructions
	* Approximate correctness of the code edits
	* Careful & clear answers to the questions
	* Correct answers to the questions
	* Slightly more than half the 1000 points will come from answering the questions. The rest will come from your edits to the code.

### Names of people you have worked with on this assignment
* List everyone's names and uniqnames who have worked on this assignment with you, **including your own name, but make sure YOUR name is first and bold**

**Avery Gleason (averyag)** <br />
Cara Canady (first three questions in class) <br />
Maggie Davidson (first three questions in class) <br />


## Questions & code instructions

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**<br />
A comment in JavaScript starts off with two forward slashes //.


* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.** <br />
In order to run JavaScript, we need a function to be defined and to be called. Our JavaScript must be enclosed in a script element, which are <script> </script> brackets.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.** <br />
There are two functions that seem similar to print. One is alert() and the other is console.log(). Alert seems to print out a message like 'hello' in a pop up box. Where console.log() seems to be printing out" directly into the console. In our code it says "hello in the console". I would use alert if I had a message I wanted the user to see. Where printing out in the console seems to be something for a developer.


* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...** <br />
I would have to comment out the line 12 alert("hello").For the new date and time I've added the code alert(new Date()).


* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.** <br />
This can be done on line 17 in the function displayInformation.  document.querySelector('h1').innerHTML = "Avery Gleason"; will produce it so my name is at the top. This line seems to be saying query the html and where ever the 'h1' html tag is found replace it with Avery Gleason.


* **What does the word `document` represent in this code? Explain briefly.** <br />
The document in our code seems to be representing the HTML structure that will be used with the browser. It a way of referencing the HTML that is being used in the browser. It seems to be it's own type of object.


* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).** <br />
document.querySelect('#items').innerHTML seems to be selecting all of the elements with the ID of items, document.getElementsByTagName('li').length  seem to be getting all the elements with a tag name that is li. Since these are set equal they are being assigned to each other.


* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**
When commenting out body.style.background = 'CCEE00' we can see the background would be white.

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.** <br />
The white border comes from line 39 border: 3px solid #FFFFF, the gray comes from the line above background-color: #etc.  I can update the hex code to get both to be blue.

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?** <br />
First, I made a new function called copyFunctionAgain.  This function is going to query our html and look for  the ID 'cheeragain'and if found, replace with O Canada.  I then edited line 72 to  <li oncopy="copyFuctionAgain()">McGill University</li>r. So when McGrill is copied the query for the ID cheeragain begins. The final part was to add a new section where the queried object would live which is line 80 - 82, where id='cheeragain' lives.

* **In the original code, when you click the button that says `Wow`, you see a text box! Wow. Explain briefly in your own words why the following code causes that to happen:**

```js
function handleClick(){
	alert("hello");
}
```
**and**

```js
<button onclick=handleClick() id="wow-button">Wow</button>
```

The function handeClick() has an alert with 'hello' writing inside. Meaning when the function is called a pop up box with "hello" will appear to the user. The last part of the code creates the actual button the user sees. When clicked, the handleClick() function runs.


* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**
Done!


### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**
The color comes from lines 7 through 12. <style type="text/css" .error{color:red;} .good{color:blue;}. A good valid response will show as blue while an error will show as red.  This code sets the rules of what colors to use for which response. The JavaScript below it writes the logic to determine what type of response is valid or an error.

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**
I googled regex=/^[a-zA-Z]+$/. Here is what I learned: This is called a regular expression. They help do pattern matching and checking if certain characters exist within text. Regex is used in the conditional on line 20.  Basically, this line is allowing us to check to see if the word input is only containing values that are acceptable IE alaphbalical letters (not symbols etc)

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**
First, python uses white space and indentation to help with conditionals, where JavaScript uses curly brackets.  Python also uses a : where Javascript does not.  JavaScript also uses 'else if' where python uses 'elif'

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**


* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

```js
$(document).ready(function(){
    $("form").submit(function(event){
```


* **Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.
