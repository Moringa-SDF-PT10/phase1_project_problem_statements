# **Problem Statement 3 - Mystery Meal Game using TheMealDB API**

You will create a **Mystery Meal Game** using [TheMealDB API](https://www.themealdb.com/api.php). In this game, users will get to "spin" for random meals, view details of the meals, and guess the cuisine or category based on the image and ingredients. At the end of 3 rounds, the app will show how many correct guesses the user made!

---

### 🔧 **Setup Instructions**

1. Create a new **PRIVATE** repository in the [Moringa-SDF-PT10](https://github.com/Moringa-SDF-PT10) GitHub Organization.  
   The naming format should be:  
   **_firstname-lastname-meal-project_**  
   (Example: `jane-doe-meal-project`)  
   _Any other repository name will **NOT** be graded._

2. In the root of your repository, create the following files:  
   - `index.html`  
   - `styles.css`  
   - `index.js`  
   If your project includes images or audio, store them in an `assets` folder.

3. Create a branch called `gh-pages` for deployment on GitHub Pages.

4. Submit the GitHub Pages link for your project:  
   Example: `https://moringa-sdf-pt10.github.io/jane-doe-meal-project/`

---

### 🎯 **Game Flow**

- A start page with a **"Start Game"** button.
- On clicking start:
  - A random meal is fetched using TheMealDB API.
  - The meal **image**, **ingredients**, and **instructions** are displayed **(excluding the name, area, and category)**.
  - User is prompted to guess the **cuisine** (e.g., Italian, Mexican) or **category** (e.g., Dessert, Seafood).
- The user gets immediate feedback after each guess (correct or incorrect).
- This repeats for **3 rounds**.
- At the end, show the user's **score** and a list of meals revealed.

---

### ✅ **Deliverables - User Stories**

As a user, I can:

1. Click a **Start Game** button to begin.
2. View a meal image and its ingredients (but not the name, area, or category).
3. Type or select my guess for the cuisine/category.
4. See feedback on whether my guess was correct or incorrect.
5. See my final score and a summary of all 3 meals at the end.
6. Restart the game by clicking a **"Restart Game"** button.

---

### 🧪 **API Endpoints You’ll Use**

- Get a random meal:  
  `https://www.themealdb.com/api/json/v1/1/random.php`

- (Optional for enhancements) Search meals by category:  
  `https://www.themealdb.com/api/json/v1/1/filter.php?c=Dessert`

- Full API docs: [https://www.themealdb.com/api.php](https://www.themealdb.com/api.php)

---

### 📝 **README Requirements**

- Project description
- How to run the app
- Technologies used
- Link to the live GitHub Pages version
- Screenshots or demo GIFs (optional but encouraged)

Use [this guide on writing good READMEs](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/) for help.

---

### 💡 **Tips**

- Use the `strCategory` or `strArea` fields for validating guesses.
- Consider using dropdowns for user input to make it easier.
- Hide all meal details that would give away the answer too easily.
- Keep your code clean and well-commented.
- Feel free to use helper functions to format the ingredients list.


