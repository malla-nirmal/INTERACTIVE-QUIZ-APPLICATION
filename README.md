# INTERACTIVE-QUIZ-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: Malla Nirmal

"INTERN ID: CT04DA698

"DOMAIN: FRONT END DEVELOPMENT

11 "DURATION: 4 WEEEKS

"MENTOR: NEELA SANTOSH

DESCRIPTION:The provided HTML document represents a simple and interactive web-based quiz application built using three core web development technologies: HTML, CSS, and JavaScript. This type of application is common in educational websites, e-learning platforms, training modules, and entertainment sites where user engagement through quizzes is essential. Let’s break down the code, the tools used, how it works, and where it is applicable in detail.

Technologies & Tools Used
HTML (HyperText Markup Language):

HTML structures the content of the webpage.

It defines the document type (<!DOCTYPE html>) and creates elements like the quiz container (<div class="container">), question section, answer buttons, feedback, and the score display at the end.

CSS (Cascading Style Sheets):

CSS is used to style the visual elements.

In this code, styles are included within a <style> block in the <head> of the document.

The CSS provides layout properties such as centering, padding, font styles, background colors, rounded corners, and button styles. For example, .btn.correct changes the background color to green when the correct answer is selected.

JavaScript:

JavaScript adds dynamic interactivity to the page.

It allows for loading questions, handling answer selection, tracking the score, and navigating through questions.

It also dynamically updates the DOM based on user interaction (e.g., showing feedback or disabling buttons after selection).

Editor/Platform Used
This code can be written and tested in any modern code editor such as:

Visual Studio Code (VS Code) – most commonly used due to its extensions and live server plugin.

Sublime Text, Atom, or Notepad++.

Online code editors such as CodePen, JSFiddle, or Replit are also excellent for testing and demonstrating such front-end applications in a browser without installing anything.

It runs on any standard web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.) since it uses client-side technologies.

Detailed Code Explanation
HTML Structure
The <body> contains a single main <div> with the class container, which acts as the visual card for the quiz.

Inside, there's:

A <div id="question"> to display the current question.

A <div id="answers"> that will dynamically populate multiple choice buttons.

A <div id="feedback"> that displays "Correct!" or "Wrong!" after each selection.

A <button id="next"> to load the next question.

CSS Styling
The body has a background and padding to center the quiz content.

The .container has a light background, shadow, rounded borders, and is centrally aligned.

Buttons are styled for better UX, with hover and click effects visually represented by color changes.

JavaScript Functionality
Data Storage:

The quiz questions are stored in a data array containing objects. Each object has a question q, options opts, and the correct answer ans.

load() Function:

Called initially and each time the user clicks "Next".

It loads the current question and options into the HTML DOM.

pick() Function:

Triggered when an answer button is clicked.

It checks if the selected answer is correct or not.

Applies appropriate styling (correct or wrong) and disables all buttons to prevent multiple answers.

Navigation:

The "Next" button calls load() for the next question or end() if it's the last one.

end() Function:

Replaces the entire quiz area with a summary score message when the quiz is complete.

Use Cases / Applicability
This quiz application can be used in several real-world scenarios:
E-Learning and Online Education Platforms:
For conducting formative assessments or chapter-end quizzes.
Helps in interactive learning by providing instant feedback.

Corporate Training:
Organizations use quiz systems for employee onboarding, compliance training, and refresher courses.

Entertainment and Trivia Games:
A fun, engaging way to test general knowledge or themed quizzes (e.g., movies, sports).

Exams and Tests Preparation Sites:
Useful in simulating MCQ-based practice exams like SAT, GRE, or competitive exams.

Classroom & School Use:
Teachers can deploy this kind of app for digital quizzes during class or homework assignments.

Surveys and Feedback:
With modification, it can be used to collect opinions or feedback by converting questions to survey format.

Conclusion
This code demonstrates how you can build a basic yet fully functional quiz app using only front-end web development tools. It emphasizes logic control with JavaScript, user interface design using HTML and CSS, and is suitable for multiple application domains. Since it is purely client-side, it's easy to deploy, fast to load, and flexible enough to enhance with additional features like timers, user login, progress bars, or storing scores using localStorage or a backend service. This kind of project also serves as an excellent foundation for beginners learning interactive web development.

 #OUTPUT

 ![Image](https://github.com/user-attachments/assets/a005a4c6-7786-4f73-818d-0501c092db14)
