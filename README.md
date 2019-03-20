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

* Fork (and clone) this repository
* Add our instructional team as a collaborator to your fork (see instructions for adding collaborators on Canvas)
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
* **Sara Gladchun (skglad)**
* Megan St. Andrew (meglynst)
* Caitlyn Helgesen (chelgese)
* Angela Chih (ahchih)
* Corbin Griffith (corbet)

## Questions & code instructions

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**

A code comment in JavaScript is // so in order to make a comment you need to put "//" before you write a comment in the code.

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**

You need to have a script tag in order to get a program to run.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**

The two methods that are similar to print:

alert()
console.log()

alert() would be something to be displayed on the browser, but the console.log would only be displayed in the console of the web browser.

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**

We would need to comment out "alert("hello")" on line 12 to get rid of the pop-up box when you load the page.
To add the date and time to pop up, we add the code:

alert(new Data())

below the commented out code on line 12, which is the data and time function.  


* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**

We replace "A name" in line 17 with our own name, so for me I replaced it with "Sara Gladchun"

* **What does the word `document` represent in this code? Explain briefly.**

'document' is part of the DOM, and represents the HTML file that we are within and allows javascript to manipulate that file.

* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**

This code is a querySelector method that is counting the number of list items (with the <li> tag) and totaling it to display it as "The number of list items for this page".

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**

The background of the page would be white because there is no color assigned in the HTML.

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**

There are gray boxes because the style of the <p> tag is assigned a background color of b3b3b3 on line 37. You could change the "#b3b3b3" to a different color. You could edit it in CSS and javascript. I changed the "#b3b3b3" code to "#4286f4" to change it to a shade of blue.

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**

I added a function called copyFunction2 and invoked that function on the list item "McGill University", and set it to display "O Canada" when McGill University if highlighted. This function is very similar to the function copyFunction that was set for the "University of Michigan" so I was able to base my code on that code.

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
The function handleClick() is a function that prompts an alert that says "hello", this function is invoked on the "wow-button" so the function is prompted when the "wow button" is clicked, which is why the box pops up upon the click.


* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**

I added the code:

function handleClick2(){
	alert("March 20, 2019");
}
on lines 40-43

and I also added the code:
<button onclick=handleClick2() id="SE-button">Spring Equinox 2019</button>

to line 83 in order to place this button underneath the "wow" button.


### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**

The error message is in red and the valid message is in blue because of the style code found on lines 7-13
found on lines 7-13.

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**

The regular expression is helping to determine whether or not the submission is actually a word. This regex is checking to make sure that all the characters (more than 1) are actually letters and not other characters. They can be upper case or lower case but they must be letters (a-z or A-Z).

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**

Within the jquerylib_sumit_example.html files, I can see an example of a conditional statement in lines 20-26.

Looking at this example, some of the main differences that I see is that the "if" is followed by the conditional statement within parentheses, and then followed by the code that should be executed if the conditional is True in {} after the parenthesis. This is similar to Python, but there are some major differences. My comparison between the two syntaxes is below:  

The syntax of JavaScript conditional statement appears to be:

if(condition){
	code to be executed
}
else{
	code to be executed
}

The syntax of Python conditional statement is:

if (condition):
	code to be executed
else:
	code to be executed

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**
The fadeOut method animates the opacity of the matched elements, and the first parameter is duration (default is 400)- so I think that this 10000 refers to milliseconds of time for the element to fade out from the screen.

Resource: http://api.jquery.com/fadeout/

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

// js
$(document).ready(function(){
    $("form").submit(function(event){

This code is wrapping the code in "document ready" so that the code will load the DOM (and all the elements) so that the code can function. Then the code is creating a .submit() event which is usually used to validate the form before submitting to the server. So this appears to be code to initiate the program - loading the DOM and creating the submission event.  

Resource: https://stackoverflow.com/questions/12252378/capturing-a-form-submit-with-jquery-and-submit/12252576 

**Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.

To add this feature to the code I added an additional "else if" statement on the conditional to check if the currentValue is equal to "hello" and, if that is true, to return "hello to you too!" rather than "nice!". I also set this as style type "good" so that this would also print out as blue.
