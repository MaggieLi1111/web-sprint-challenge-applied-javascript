# Applied JavaScript Sprint Challenge

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past sprint and apply them in a concrete project. This sprint explored **Applied JavaScript**. During this sprint, you studied **DOM and components**. In your challenge this week, you will demonstrate your mastery of these skills by creating **an online Lambda newspaper**.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge.

## Project Set Up

- [ ] Fork and clone the repo. Delete your old fork from Github first if you are repeating this Unit.
- [ ] Open the assignment in Canvas and click on the "Set up git" option.
- [ ] Push your first commit: `git commit --allow-empty -m "first commit" && git push`.
- [ ] Check to see that Codegrade has accepted your git submission.

## Project Instructions

### Introduction

You are going to create a Lambda Newspaper. Your job is going to be to create the components that make up the newspaper's home page.

In meeting the minimum viable product (MVP) specifications listed below, your project should look similar to the image linked below:

[Lambda Times](https://tk-assets.lambdaschool.com/cac4803c-6e8f-4846-be0e-b20d82a34a73_lambda-times.png)

### Instructions

- [ ] Navigate to the root of the project with your command line.
- [ ] Run `npm install` to download the dependencies listed in the `package.json` file.
- [ ] Run `npm start` to compile the project and serve it.
- [ ] Navigate Chrome to `http://localhost:3000`
- [ ] In a separate terminal, run `npm test` to run tests.

**Steps Required for MVP:**

- [ ] Steps 1 and 2 are explained inside the `src/components/header.js` file.
- [ ] Steps 3 and 4 are explained inside the `src/components/tabs.js` file.
- [ ] Steps 5 and 6 are explained inside the `src/components/card.js` file.

**Important Notes:**

- Please **do not move or rename existing files** or folders.
- If your development server stops "auto reloading", manually kill it with `CTRL+C` and restart it.
- Do not change the `package.json` file except to install libraries with NPM (Axios is _already_ in the `package.json`).
- In your solution, it is essential that you follow best practices and produce clean and professional results.
- Schedule time to review, refine, and polish your work, including spell-checking and grammar-checking.
- It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Submission format

- [ ] Submit via Codegrade by committing and pushing any new changes to the *main* branch.
- [ ] Check Codegrade for automated feedback.
- [ ] Check Codegrade in the days following the Sprint Challenge for reviewer feedback.
- [ ] Any changes pushed after the deadline will not receive any feedback.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. What is the DOM?
Document Object Model. 
It provides the interface that code can manipulate the webpage. 
When the web page is loaded into a browser, the browser first looks for the HTML file. 
Next, the browser uses the HTML file as a blueprint or instructions on building the page (this coupled with the CSS file later). 
Finally, the browser parses these instructions and builds a model for the page's look and act using Javascript. 
This model is a Javascript Object containing every element in order on the page.

2. What is an event?
Events are actions or occurences that happen in the system when programming.
 which the system tells you about so you can respond to them in some way if desired. 
 For example, click button, moving the mouse, scroll, press key, drag and drop, zoom, or any number of user interactions. Every user interaction with a site is an event.

3. What is an event listener?
An event listener is a procedure or a funciton in a computer program that waits for an event to occur. 
For example, when the user click or move the mouse, press a key on the keyboard, disk I/O, network activity, or an internal timer or interrupt. 
The listener is programmed to react to an input or signal by calling the event's handler.

4. Why would we convert a NodeList into an Array?
Nodelist are collections of nodes, usually returned by properties such as Node.childNodes and methods such as document.querySelectorArr(); 
Nodelist is not an array, just array-like object, it is impossible to iterate over it with forEach(). This means that if you pass a NodeList where you expect an Array it'll probably work unless you used one of the Array methods which will fail. 
Browsers can implement NodeList under the hood however they like. Document.querySelectorAll can return a lightly wrapped internal data structure instead of marshalling to a JavaScript array. 
This could save a lot of copying and makes it easier to maintain a "live" NodeList that updates as the DOM changes. 
If you're returning or passing on a node list to other parts of your code because programmers likely expect arrays so exposing a non-array could cause subtle bugs.

5. What is a component?
Components are small reusable pieces of code that can be used to build elements sharing functionality and styling. 
A Component comprises several parts: HTML, CSS, or Javascript brought together as a combination building blocks in a website or application. 