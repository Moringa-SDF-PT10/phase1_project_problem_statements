# **Problem Statement 4 – Crypto Guess Challenge using CoinPaprika API**

You will build a fun and educational **Crypto Guess Challenge** game using the [CoinPaprika API](https://api.coinpaprika.com/). In this game, the user is presented with real data for a mystery cryptocurrency — but without revealing its name. The user must **guess** the correct coin based on hints like market cap, price, rank, and symbol.

---

### 🔧 **Setup Instructions**

1. Create a new **PRIVATE** repository in the [Moringa-SDF-PT10](https://github.com/Moringa-SDF-PT10) GitHub Organization.  
   Use the naming convention:  
   **_firstname-lastname-crypto-project_**  
   Example: `jane-doe-crypto-project`  
   _Other names will **NOT** be graded._

2. Create the following files in the root of your repository:
   - `index.html`  
   - `styles.css`  
   - `index.js`  
   If needed, store icons or images in an `assets` folder.

3. Create a `gh-pages` branch and deploy your project using GitHub Pages.

4. Submit your GitHub Pages link:  
   Example: `https://moringa-sdf-pt10.github.io/jane-doe-crypto-project/`

---

### 🎮 **Game Flow**

- Start screen with a **"Start Challenge"** button.
- On click:
  - A **random coin** is selected using CoinPaprika.
  - Display **hints only**, such as:
    - Symbol (e.g., BTC)
    - Rank (by market cap)
    - Current price (USD)
    - Market cap value
    - First letter of coin name
    - Launch year (if available)
  - User must **guess the coin name**.
- Feedback is shown (correct or incorrect).
- This is repeated for **3 rounds**.
- Display total correct guesses and reveal the coin names.

---

### ✅ **User Stories**

As a user, I can:

1. Click a **Start Challenge** button to begin.
2. See a hint-based preview of a cryptocurrency (without seeing the name).
3. Type in my guess for the coin's name.
4. Get instant feedback after each guess.
5. See my total score and the actual names after 3 rounds.
6. Restart the challenge with a **"Restart Game"** button.

---

### 🧪 **CoinPaprika API Endpoints**

- Get all coins:  
  `https://api.coinpaprika.com/v1/coins`

- Get coin details by ID (e.g., `btc-bitcoin`):  
  `https://api.coinpaprika.com/v1/tickers/{coin_id}`

- Example:
  ```bash
  GET https://api.coinpaprika.com/v1/tickers/btc-bitcoin
  ```

  Response fields of interest:
  - `name`
  - `symbol`
  - `rank`
  - `quotes.USD.price`
  - `quotes.USD.market_cap`

---

### 📘 **README Requirements**

Include the following:
- Project summary
- How to play
- Technologies used
- How to run the app locally
- Link to the live GitHub Pages version
- Screenshots (optional but nice)

Use this guide for reference: [How to write a good README](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)

---

### 💡 **Bonus Tips**

- Normalize coin names (e.g., lowercase) for easy comparison.
- Show partial hints like the **first letter** of the name or number of characters.
- Add animations or icons for user feedback (✔️ / ❌).
- Use a timeout or "Next Round" button to move between rounds.
