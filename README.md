# Interactive-Quiz-Page

1. Start Button and Info Box:
Feature: When the user clicks the "Start Quiz" button, it displays an info box with instructions.
Implementation: It uses event listeners to show and hide the info box when buttons are clicked.

2.Continue Button:
Feature: After reading the instructions, the user can click the "Continue" button to start the quiz.
Implementation: It hides the info box and displays the quiz questions.

3.Timer:
Feature: A timer counts down from 15 seconds for each question.
Implementation: Implemented using JavaScript's setInterval, clearInterval, and updating the DOM to show the remaining time.

4.Question Counter:
Feature: It displays the current question number out of the total number of questions.
Implementation: Updated dynamically as the user navigates through questions.

5.Next and Previous Buttons:
Feature: Allows users to navigate between questions using "Next" and "Previous" buttons.
Implementation: Event listeners on these buttons update question content, counters, and timers accordingly.

6.Options and Answer Validation:
Feature: Users can select options, and the code validates whether the selected answer is correct.
Implementation: Event listeners on options trigger validation functions, updating the user's score and providing visual feedback.

7.Result Display:
Feature: After answering all questions, the user sees a summary of their score.
Implementation: The result box is displayed with a score message based on the user's performance.

8.Restart and Quit Buttons:
Feature: Users can restart the quiz or quit to reload the page.
Implementation: Event listeners on these buttons reset the quiz or reload the page.

9.Timeline Animation:
Feature: A visual timeline bar indicates the remaining time for each question.
Implementation: Implemented using CSS and JavaScript to dynamically update the timeline width.

10.Performance Grading:
Feature: The user's score is used to determine their performance.
Implementation: A function calculates the user's performance based on their score.

11.Storing Remaining Time and Timeline Width:
Feature: The quiz remembers the remaining time and timeline width when navigating between questions.
Implementation: Variables store the remaining time and timeline width when the "Next" and "Previous" buttons are clicked, ensuring a seamless transition.
