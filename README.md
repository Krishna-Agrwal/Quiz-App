Interactive Quiz App

Overview :
The Interactive Quiz App is a dynamic and engaging web-based application designed to present quiz questions with a sleek, user-friendly interface. This app allows users to test their knowledge across various topics while providing real-time feedback and progress tracking.

Features :
Dynamic Questions: A variety of multiple-choice questions covering diverse topics.
Responsive Design: Ensures compatibility with different screen sizes and devices.
Real-Time Timer: Countdown timer for each question to enhance challenge.
Animated Effects: Subtle animations for an engaging user experience.
Progress Bar: Visual representation of the time left for each question.
Score Tracking: Displays the user's score at the end of the quiz.
Emoji Feedback: Displays topic-related emojis for added fun and context.

Technologies Used:
HTML: Structure of the web application.
CSS: Styling for the application, including animations and responsive design.
JavaScript: Logic and interactivity for the quiz functionality.

How to Use:
Open the Application: Open the index.html file in any modern web browser.
Start the Quiz: The first question loads automatically.
Select an Answer: Click on one of the options to select your answer.
Next Question: Click the "Next" button to move to the next question.
Timer: Answer the question before the timer runs out.
End of Quiz: After the final question, a popup will show your total score.

Customization:

Add More Questions:
Edit the quizData array in the JavaScript section.
Add an object for each new question with the following keys:
{
  question: "Your question here",
  options: ["Option 1", "Option 2", "Option 3", "Option 4"],
  correct_answer: "Correct option text",
  emoji: "Emoji relevant to the question"
}

Change Timer Duration:
Modify the timeLeft value in the startTimer() function.

Future Enhancements:
Leaderboard: Add functionality to track and display high scores.
Categories: Allow users to select a quiz category.
User Authentication: Enable login functionality to save progress and scores.
Sound Effects: Add sounds for correct/incorrect answers.

Credits
Background Image: Courtesy of Unsplash.
Font: "Montserrat" by Google Fonts.
