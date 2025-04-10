# Problem Statement 1 - Trivia Project
You are required to create an interactive quiz game with single or multiple choice questions.

The game should include:
- A start page with a "Start Quiz" button.
- Multiple-choice questions with options. Only one answer is correct.
- A score tracker that keeps track of how many questions were answered correctly.
- At the end of the quiz, show the user’s score and an option to restart the quiz.

## Setup

1.  Create a new  **PRIVATE**  repository in this GitHub Organization ([Moringa-SDF-PT10.](https://github.com/Moringa-SDF-PT10 "Link")). Ensure your repository has a name in the following format;  _firstname-lastname-trivia-project_  (Example: **jane-doe-trivia-project**).  _Take note, any other repository name will  **NOT**  be graded_.
2. Create the `index.html`, `styles.css` and `index.js` files in the root of your repository. Should your project have images, create an `assets` folder where you will store your images.
3. Ensure your project has a branch called `gh-pages` will be used to deploy your project to GitHub Pages.
4. You will submit the link for your application's GitHub Pages link: ie _https://moringa-sdf-pt10.github.io/jane-doe-trivia-project/_

**Before you submit!** Save and run your code to verify that it works as you expect. If you have any methods that are not working yet, feel free to leave comments describing your progress.

> You **MUST** have a well-written **README** in your repository. Ensure your markdown renders correctly before submission. You can use [Visual Studio Code Markdown preview.](https://code.visualstudio.com/docs/languages/markdown#_markdown-preview) to see how it would appear on your **GitHub** repository.

#### Resources

-   [How to write a good README.](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/ "Link")

## Deliverables

As a user, I can:

1. Click on "Start Quiz" button to start answering questions.
    
2.  Click on the answer to a question and I should get a notification on where it's correct or not.  **No persistence is needed**.
    
3.  See my total score on a Score Board after I've answered all the questions.  **No persistence is needed**.

4. See all the correct answers to the questions I got wrong.  **No persistence is needed**.

5. Click on "Restart Quiz" to restart the quiz with either the same or different set of questions.

> The Trivia DB API can be accessed at https://opentdb.com/api_config.php
    

### Bonus Deliverables

These bonus deliverables are here if you want an extra challenge and won't affect your score.  **Make sure to commit your work to save your progress before attempting the bonus deliverables!**

As a user, I can:
1.  Select the number of questions, the category, difficulty and type of questions I want to be quizzed on and the webpage should make the fetch request to display the quiz.

2.  See a timer that counts down how much time I have to answer a single question
    
3.  Click on a "Next Question" button to see the next question instead of displaying all the questions in one page.
    
4.  A timer that shows how long I've taken to answer all the questions.
