# Currency-Converter
# 🌍 Currency Converter Web App

A simple and elegant **Currency Converter** web application built using **HTML**, **CSS**, and **JavaScript**.  
It fetches **real-time exchange rates** using the **[Fawaz Ahmed Currency API](https://github.com/fawazahmed0/currency-api)** and displays live conversions between any two currencies along with country flags.

---

## 🚀 Features

- 🌐 Real-time exchange rates using a public API  
- 🏳️ Dynamic country flag updates  
- 🔁 Easy currency swap between “From” and “To” fields  
- 💰 Automatic conversion calculation  
- 🎨 Clean and responsive UI  

---

## 🧩 Tech Stack

- **HTML5** – Structure of the app  
- **CSS3** – Styling and layout  
- **JavaScript (Vanilla JS)** – Logic and API integration  
- **Fawaz Ahmed Currency API** – Live exchange rate data  
- **Flags API** – Country flag images  

---

## 📁 Project Structure

currency-converter/
│
├── index.html # Main HTML file
├── style.css # Styling for the app
├── app.js # Core JS logic and API handling
├── codes.js # Currency-country mapping
└── README.md # Project documentation


---

## ⚙️ How It Works

1. The user selects two currencies and enters an amount.  
2. On clicking **Convert**, the app fetches the exchange rate from the **Currency API**.  
3. The result is dynamically calculated and shown on the screen.  
4. The country flags update automatically based on the selected currencies.

---

## 🧠 Flowchart

```mermaid
flowchart TD
A[Start App] --> B[User selects 'From' and 'To' currencies]
B --> C[App fetches data from Currency API]
C --> D[Retrieve exchange rate JSON]
D --> E[Calculate converted amount]
E --> F[Display conversion result on screen]
F --> G[Update flags dynamically]
G --> H[End]

