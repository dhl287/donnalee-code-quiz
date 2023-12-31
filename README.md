# Code-Quiz

## Description
This challenge required me to create a code quiz that allows the user to start the quiz, review and answer three code questions, and see their score at the end of the quiz. The user will also enter their initials to log their score, and their score will be added to the list of "High Scores". The goal was to create all code from scratch and make sure all code matched the acceptance criteria. 

## Installation
My responsibility was to satisfy the acceptance criteria, create a new repository on GitHub, commit and push any changes to the repository, and deploy to GitHub Pages to view the website live. The HTML code is available on index.html, the CSS code is available on style.css, and JavaScript code is available on script.js in the donnalee-code-quiz folder. The High Scores page was created with a new set of HTML (highpages.html), CSS (highpages.css), and JavaScript (highpages.js) code, which is all saved in the donnalee-code-quiz folder. All code was created from scratch.

## Usage
The main page shows the link to the High Scores on the top left and a Timer on the top right. The title of the quiz as well as the Start button is visible. To start the quiz, the user will click the Start button. The timer of 60 seconds will start once the Start button has been clicked. 

![image](https://github.com/dhl287/donnalee-code-quiz/assets/133473429/1e6a243c-b19b-4c1d-bfa5-759b9a7a7bcc)

Once the quiz has been started, the user will be presented with three questions and three choices for each question. When a question has been answered correctly, the user will click Submit to see the next question, and the timer will continue. When a question has been answered incorrectly, the user will click Submit to see the next question, and the timer will deduct 10 seconds.

![image](https://github.com/dhl287/donnalee-code-quiz/assets/133473429/84405e8c-16c0-464d-834b-9890294af38c)

Once the quiz has been completed, the last page will show the user's score and an input field to add their initials. The score is logged in the console, but I was unable to figure out how to log the user's initials in the console or in local storage. The if/else statement added in the submitInitials() function is only triggering an alert asking for the initials to be between 2-3 characters. Ideally, the initials for anyone who saves their initials should be saved in the local storage (setItem()), and these initials should then be shown on the High Scores Page (getItem()). 

![image](https://github.com/dhl287/donnalee-code-quiz/assets/133473429/e051e033-6ec2-43da-bdc7-850636833660)
![image](https://github.com/dhl287/donnalee-code-quiz/assets/133473429/ac2a336e-ae30-4b1f-a89a-94ed7168067b)

The challenge has been deployed, but not all criteria was met. 

## Credits
I would like to credit the following sources for study materials in adding all code: 

* [How to make a simple JavaScript quiz] (https://simplestepscode.com/javascript-quiz-tutorial/)
* [Create a quiz application using JavaScript] (https://www.geeksforgeeks.org/how-to-create-a-simple-javascript-quiz/#)
* [JavaScript Tutorial] (https://www.w3schools.com/js/default.asp)
* [How to Make a Quiz App using HTML CSS Javascript - Vanilla Javascript Project for Beginners Tutorial] (https://www.youtube.com/watch?v=f4fB9Xg2JEY&ab_channel=BrianDesign)

## License
There is no license associate with Donna Lee - Portfolio.

