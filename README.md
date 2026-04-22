# 🏠 Telegram Real Estate Price Bot

A Telegram bot that estimates real estate prices in real time using a Machine Learning model.

This updated version goes beyond basic m² prediction by including a more complete simulation flow with property type, apartment subtype, zone, and automatic property classification based on size.

👉 Try the bot here: https://t.me/devksr_corretorex_bot

---

## 📌 About the Project

This project was developed during my **Artificial Intelligence Programming course at SENAI**.

The idea is to simulate a smarter real estate assistant on Telegram, capable of generating price estimates based on different property characteristics.

---

## ⚙️ Main Features

- Real-time price estimation on Telegram
- Property type selection:
  - house
  - apartment
- Apartment subtype selection:
  - common
  - penthouse
- Zone-based prediction
- Automatic property standard classification by m²
- Expanded dataset for a more complete prediction flow

---

## 🧠 How It Works

The bot reads the dataset, trains a **Linear Regression** model, and interacts with the user directly on Telegram.

The prediction considers:

- property type
- apartment subtype
- zone
- size in m²

---

## 🤖 Commands

- `/start` → start interaction
- `/ajuda` → usage instructions
- `/comandos` → list commands
- `/novo` → start a new simulation
- `/sobre` → project overview
- `/encerrar` → end the session

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- pyTelegramBotAPI

---

## 📂 Project Structure

```text
.
├── iag_expandido.py
├── dados_imobiliaria_expandido.csv
└── README.md
```

---

## ▶️ How to Run

```bash
pip install pandas scikit-learn pyTelegramBotAPI
```

Set your Telegram bot token in the code:

```python
TOKEN = "your_token_here"
```

Run the project:

```bash
python iag_expandido.py
```

---

## ⚠️ Notes

* This project was built for learning purposes
* Predictions are approximations based on the dataset
* Do not expose your real Telegram bot token publicly

---

## 👨‍💻 Author

Kevin Silva Ramos
Developed during SENAI AI course

