# 🏠 Telegram Real Estate Price Bot

This project is an older version of a Telegram bot that estimates property prices based on size (m²) using a simple Machine Learning model.

Although it is now outdated compared to the version currently available in the `main` branch, with fewer features and a simpler structure, it still fulfills its original purpose well.

👉 Try the bot here: https://t.me/devksr_bot

---

## 📌 About the Project

This bot was developed as part of my **Artificial Intelligence Programming course at SENAI**.

The main idea is simple: based on a dataset of real estate sales, the model learns the relationship between property size and price, and then uses this information to estimate new values in real time directly on Telegram.

This version represents an earlier stage of the project, before later improvements and added features.

---

## ⚙️ How It Works

- The bot reads a dataset (`dados_imobiliaria.csv`)
- It trains a **Linear Regression model** using scikit-learn
- The user sends a property size (in m²)
- The bot returns an estimated price

### Example

```text
User: 120
Bot: Estimated price: R$ XXX.XXX,XX
```

---

## 🤖 Bot Commands

* `/start` → start interaction
* `/ajuda` → instructions on how to use
* `/comandos` → list all commands
* `/novo` → start a new simulation
* `/encerrar` → end the session

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* pyTelegramBotAPI

---

## 📂 Project Structure

```text
.
├── corretor_iag.py
├── dados_imobiliaria.csv
└── README.md
```

---

## ▶️ How to Run the Project

1. Install the dependencies:

```bash
pip install pandas scikit-learn pyTelegramBotAPI
```

2. Replace the bot token in the code:

```python
TOKEN = "your_token_here"
```

3. Run the script:

```bash
python corretor_iag.py
```

---

## ⚠️ Notes

* This is a simple project created for learning purposes
* This version is older and has fewer features than the current version in the `main` branch
* The model uses basic linear regression, so predictions are approximations
* Do not expose your real Telegram bot token publicly

---

## 🚀 Future Improvements

This version is no longer the main focus of development, but possible improvements originally considered included:

* Improve the model with more features (location, rooms, etc.)
* Deploy the bot online instead of running locally
* Add better user interaction

For the most updated version of the project, check the `main` branch.

---

## 👨‍💻 Author

Kevin Silva Ramos
Developed during SENAI AI course
