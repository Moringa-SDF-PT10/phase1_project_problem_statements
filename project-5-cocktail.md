# **Problem Statement 5 - Cocktail Quiz Project 🍸**

You're tasked with creating a fun and interactive **Cocktail Quiz Game** using the [CocktailDB API](https://www.thecocktaildb.com/api.php). In this quiz, the player will be tested on their knowledge of cocktail ingredients, names, and categories.

---

## 🧾 Game Requirements

The game should include:

- A start page with a **"Start Quiz"** button.
- Multiple-choice questions about cocktails (e.g., "Which ingredient is *not* in a Margarita?" or "Which glass is used for a Martini?").
- A score tracker to keep track of the number of correct answers.
- At the end of the quiz, show the total score and offer an option to restart the game.

---

## 🛠️ Setup

1.  Create a new **PRIVATE** repository in this GitHub Organization ([Moringa-SDF-PT10](https://github.com/Moringa-SDF-PT10 "Link")).  
    Name your repository using the format:  
    **_firstname-lastname-cocktail-quiz_**  
    Example: `jane-doe-cocktail-quiz`  
    _Other names will **NOT** be graded._

2. In the root of the project, create the following files:
    - `index.html`
    - `styles.css`
    - `index.js`  
    Create an `assets/` folder for storing images or icons if needed.

3. Create a `gh-pages` branch for deployment and submit the GitHub Pages URL:  
   Example: `https://moringa-sdf-pt10.github.io/jane-doe-cocktail-quiz/`

---

## 🧪 Deliverables

As a user, I can:

1. Click on the **"Start Quiz"** button to begin the quiz.

2. Answer cocktail-related multiple-choice questions one by one.

3. Get immediate feedback on whether my answer was correct or not. (**No persistence required**)

4. See my total score at the end of the quiz on a Score Board. (**No persistence required**)

5. View all the **correct answers** for questions I got wrong. (**No persistence required**)

6. Click on **"Restart Quiz"** to try again with a fresh set of questions.

---

## 🔗 CocktailDB API Endpoints

- Get a random cocktail:  
  `https://www.thecocktaildb.com/api/json/v1/1/random.php`

- Search cocktail by name:  
  `https://www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita`

- List all ingredients:  
  `https://www.thecocktaildb.com/api/json/v1/1/list.php?i=list`

- Filter cocktails by ingredient, glass type, category, etc.  
  Example:  
  `https://www.thecocktaildb.com/api/json/v1/1/filter.php?i=Gin`

Use the API to dynamically generate your questions (e.g., "Which of the following is **not** in this drink?", "What glass is this drink served in?", etc.)

---

## 📘 README Requirements

Your README should include:
- A summary of the project
- How to play the quiz
- Technologies used
- How to run the app locally
- GitHub Pages link
- Screenshots (optional but recommended)

Use [this guide](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/) to structure your README.

---

## 🚀 Bonus Deliverables (Optional)

As a user, I can:

1. Select **quiz categories**, such as:
   - Guess the cocktail by image
   - Ingredients quiz
   - Glassware quiz
   - Alcoholic vs non-alcoholic

2. See a **timer** for each question.

3. Click **Next Question** instead of showing all questions on one page.

4. See a **total time taken** to complete the quiz.

5. Get visual hints (like glass icons or drink thumbnails from API).
