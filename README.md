RANDOM QUESTION GENERATOR
=================
It's trivia time!

![](https://media.giphy.com/media/C9EdMKeLbb80dv4OVI/giphy.gif)

There are countless apps available that allow us to test our knowledge of useless facts and figures. Today we are going to work with a built in data set in order to generate a mini-quiz app!

GOAL
------------
Your goal today is to build an app that (1) generates a random question from a set list of questions, (2) generates a resposne to the same question, and (3) accepts user question/answer submissions. If you are ready for a challenge, you will also have the opportunity to figure out how to delete specific questions from the question bank! 

![Working App](https://media.giphy.com/media/S7QTorIdwE6yZ6IkNG/giphy.gif)

TASKS
------------
To complete this task today, you'll need to utlize `addEventLister()`, `querySelector()`, and lists (along with other programming structures that we have learned!).
1. **`querySelector()`**: Declare a variable and select for using `querySelector()` for all items on the page that you wish to select for. Do this near the top of the file.
2. **`addEventListener()` AND BUTTONS**: Attach an event listener to the random quesiton button. When the button is clicked, print a random quesiton to the HTML element with an id of questionOutput.
3. **`addEventListener()` AND BUTTONS**: Attach an event listener to the 'Give me the answer' button. When the button is clicked, print out the answer to the random quesiton to the HTML element with an id of answerOutput.
4. **UPDATE QUESTION BANK**: Everytime you click the first submit button (`id="questionSubmit"`), the questionBank list should update with the value that is contained within the the text field. After hitting submit, the value should be accessable when you click the random question button.
5. **UPDATE ANSWER BANK**: Everytime you click the second submit button (`id="answerSubmit"`), the answerBank list should update with the value that is contained within the the text field. After hitting submit, the value should be accessable when you click the "Give me the answer" button.
6. **CHALLENGE**: Modify the HTML to create a delete button. When the button is clicked, a queston and its corresponding answer choice should be removed from the questionBank and answerChoice list. **STRETCH**: Allow the use to remove a question based on their input (e.g. type in the number 1 and it removes the first question and answer from the two lists).
7. **DOUBLE SUPER BONUS CHALLENGE**: Create an input field in the HTML so that the user can answer the question. When they submit their answer, return a message to the user and let them know if they got the question correct or incorrect. Keep track of how many right and wrong answers the user has got. 
