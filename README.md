# 🏠 Telegram Real Estate Price Bot

This project is a Telegram bot that estimates property prices based on the size (m²) using a simple Machine Learning model.

👉 Try the bot here: https://t.me/devksr_bot

---

## 📌 About the Project

This bot was developed as part of my **Artificial Intelligence Programming course at SENAI**.

The idea is simple: based on a dataset of real estate sales, the model learns the relationship between property size and price, and then uses this to estimate new values in real time directly on Telegram.

---

## ⚙️ How It Works

- The bot reads a dataset (`dados_imobiliaria.csv`)
- It trains a **Linear Regression model** using scikit-learn
- The user sends a property size (in m²)
- The bot returns an estimated price

### Example

```
User: 120
Bot: Estimated price: R$ XXX.XXX,XX
```

---

## 🤖 Bot Commands

- `/start` → start interaction
- `/ajuda` → instructions on how to use
- `/comandos` → list all commands
- `/novo` → start a new simulation
- `/encerrar` → end the session

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- pyTelegramBotAPI

---

## 📂 Project Structure

```
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

- This is a simple project for learning purposes
- The model uses basic linear regression, so predictions are approximations
- Do not expose your real Telegram bot token publicly

---

## 🚀 Future Improvements

- Improve the model with more features (location, rooms, etc.)
- Deploy the bot online (instead of running locally)
- Add better user interaction

---

## 👨‍💻 Author

Kevin Silva Ramos  
Developed during SENAI AI course
