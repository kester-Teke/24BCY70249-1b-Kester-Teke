imple Banking UI

A simple banking web application that allows users to *deposit and withdraw money* with *real-time balance updates*.  
The balance is stored using *localStorage*, so it persists even after refreshing or reopening the browser.

---

## 📌 Features

- 💰 Real-time balance update
- ➕ Deposit money
- ➖ Withdraw money with insufficient balance validation
- 💾 Persistent balance using localStorage
- 📱 Responsive UI for mobile and desktop
- 🎨 Clean and modern design using CSS

---

## 🛠️ Technologies Used

- *HTML5* – Structure of the web page
- *CSS3* – Styling and responsive layout
- *JavaScript (ES6)* – Logic for deposit, withdraw, and storage
- *localStorage API* – Persistent data storage

---

## ⚙️ How It Works

- The application starts with a *default balance of 1000*
- Users enter an amount and click:
  - *Deposit* → Adds money to balance
  - *Withdraw* → Subtracts money if sufficient balance exists
- Invalid inputs and insufficient balance trigger error messages
- Balance is saved in the browser using localStorage

---

## 🧠 JavaScript Logic Overview

- localStorage.getItem() → Retrieves saved balance
- localStorage.setItem() → Stores updated balance
- parseFloat() → Converts input to decimal number
- addEventListener() → Handles button clicks and input changes
- DOM manipulation updates balance and error messages dynamically

---

## 📸 Preview

The application displays:
- Current balance
- Input field for amount
- Deposit and Withdraw buttons
- Error messages for invalid actions

---

## 👤 Author
