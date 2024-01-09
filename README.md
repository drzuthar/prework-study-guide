# Study Guide for bootcamp
## Description

This is a front end web application that is made to inform the user on the basics and fundamentals of web design and overall create an 
informantive study guide for myself and others as refrence.

The motivation of this project was to inform the user on simple things that are teh core fundamentals of web developent, this web application
was created to try and give guidance to first starting web developers, and to kick off my coding skills.
I built this project to give my footprint in codind and overall showcase what i am capable of showcasing on the web and to others.
The problem that this weba pplication solves is that it informs the user more about what kinds of language and intergrated in coding.
While building this web applicaiton I learned a lot abbout how to use reffrences and certain types of features that allow for the 
web application to be more aethically pleasing and interactive for the user/

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

The proccess of installing my project step-by-step


- create and index.html file and start adding starter code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./assets/style.css">
    <title>Prework Study Guide</title>
  </head>
  <body>
    <header id="header">
      <h1>Prework Study Guide</h1>
      <img src="./assets/bowtie-cat.png" alt="Profile image of cat wearing a bow tie." />
      <h2>✨ Open the Console to See What's Happening ✨</h2>
    </header>
    <main>
      <section class="card" id="html-section">
        <h2>HTML</h2>
        <ul>
        <li>The head element contains information about the webpage.</li>
        <li>The body element represents the visible content shown to the user.</li>
      </ul>
      </section>
   
      <section class="card" id="css-section">
        <h2>CSS</h2>
        <ul>
          <li>What i have learned so far about CSS is that the styling sheet of what
            you explain and format in the code has to be organized and read claery to the
            user and overall adds apeal and asethic to the webpage, and that assigning propeties
            and adding value to properties.
          </li>
        </ul>
      </section>
   
      <section class="card" id="git-section">
        <h2>Git</h2>
        <ul>
          <li>git status: checks what branch we are currently on</li>
          <li>git checkout -b branch-name: creates a new branch and switches to it</li>
        </ul>
      </section>
   
      <section class="card" id="javascript-section">
        <h2>JavaScript</h2>
     <ul>
        <li>A variable is a named container that allows us to store data in our code.</li>
        <li>Control flow is the order in which a computer executes code in a script.</li>
     </ul>
      </section>
    </main>

    <footer>
      <p>I can code!</p>
    </footer>
    <script src="./assets/script.js"></script>
  </body>
</html>
  

- create a style.CSS file and start adding starter code

* { 
    margin: 0;
    padding: 0;
}

header,
footer {
    width: 100%;
    height: 120px;
    background-color: blue;
    color: white;
}

h1,
h2 {
    text-align: center;
}

img {
    display: block;
    height: 50px;
    width: 50px;
    margin-left: auto;
    margin-right: auto;
}

ul {
    padding-left: 40px;
    font-size: 20px;
}

p {
    text-align: center;
    font-size: 30px;
  }
  .card {
    width: 80%;
    margin: 40px auto;
    border: 5px solid gray;
    box-shadow: 5px 10px #888888;
  }



-create a Scipt.js file and start working on the javascipt 

var topics = ['HTML', 'CSS', 'Git', 'JavaScript'];
var randomTopic = topics[Math.floor(Math.random() * topics.length)];

function listTopics() {
 for (var x = 0; x < topics.length; x++) {
   console.log(topics[x]);
 }
}

function selectTopic() {
 if (randomTopic === 'HTML') {
   console.log("Let's study HTML!");
 } else if (randomTopic === 'CSS') {
   console.log("Let's study CSS!");
 } else if (randomTopic === 'Git') {
   console.log("Let's study Git!");
 } else if (randomTopic === 'JavaScript') {
   console.log("Let's study JavaScript!");
 } else {
   console.log('Please try again!');
 }
}

console.log('Here are the topics we learned through Prework:');
listTopics();
console.log('Which topic should we study first?');
selectTopic();



What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.

## Usage wrote each section has notes topics htmlcss and hava ahit fevtools coslonse 

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative file path, add it to your README using the following syntax:

![alt text](assets/images/screenshot.png)

## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.

## License

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).

---

🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't necessary, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, list them here.

## How to Contribute

If you created an application or package and would like other developers to contribute to it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them here.
