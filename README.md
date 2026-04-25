# Telegram Real Estate Price Bot

A Telegram bot that estimates real estate prices in real time using a Machine Learning model.

This updated version includes a more complete simulation flow, considering property type, apartment subtype, zone, size in m², and automatic property classification.

Try the bot here: [https://t.me/devksr_corretorex_bot](https://t.me/devksr_corretorex_bot)

## About

This project was developed during my Artificial Intelligence Programming course at SENAI.

The idea is to simulate a smarter real estate assistant on Telegram, capable of generating price estimates based on different property characteristics.

## Main features

The bot includes:

* real-time price estimation on Telegram
* property type selection
* apartment subtype selection
* zone-based prediction
* automatic property standard classification by m²
* expanded dataset for a more complete prediction flow

## How it works

The bot reads the dataset, trains a Linear Regression model, and interacts with the user directly on Telegram.

The prediction considers:

* property type
* apartment subtype
* zone
* size in m²

## Commands

Available commands:

* `/start` - start interaction
* `/ajuda` - usage instructions
* `/comandos` - list commands
* `/novo` - start a new simulation
* `/sobre` - project overview
* `/encerrar` - end the session

## Technologies

* Python
* Pandas
* Scikit-learn
* pyTelegramBotAPI

## Project structure

```
.
├── iag_expandido.py
├── dados_imobiliaria_expandido.csv
└── README.md
```

## How to run

Install the dependencies:

```
pip install pandas scikit-learn pyTelegramBotAPI
```

Set your Telegram bot token in the code:

```
TOKEN = "your_token_here"
```

Run the project:

```
python iag_expandido.py
```

## Important note

This project was built for learning purposes.

The predictions are approximations based on the dataset and should not be used as official real estate evaluations.

Do not expose your real Telegram bot token publicly.

## Author

Kevin Silva Ramos

Developed during SENAI AI course.
