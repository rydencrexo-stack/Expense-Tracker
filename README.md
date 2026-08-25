# 💰 MoneyTrack — Expense Tracker

A simple and responsive **personal finance tracker** built using **HTML, CSS, and JavaScript**.

MoneyTrack helps you keep track of your **income, expenses, transactions, and available balance** directly from your browser.

---

## ✨ Features

- 💵 Add income
- 💸 Add expenses
- 📊 Automatically calculate total income
- 📉 Automatically calculate total expenses
- 💰 Calculate available balance
- 🏷️ Categorize expenses
- 📅 Select transaction dates
- 🧾 View recent transactions
- 🗑️ Delete individual transactions
- 🧹 Clear all transactions
- 📈 View spending by category
- 💾 Automatically save data using browser `localStorage`
- 🔄 Data remains available after refreshing the page
- 📱 Responsive design for desktop and mobile
- 🔒 No external database required

---

## 🧮 How Balance Works

MoneyTrack automatically calculates your available balance:

```text
Available Balance = Total Income - Total Expenses
````

### Example

```text
Income       ₹50,000
Expenses     ₹18,500
--------------------
Balance      ₹31,500
```

When you add an expense, it is deducted from your available balance.

When you add income, it is added to your available balance.

---

## 🏷️ Expense Categories

You can organize expenses into categories such as:

* 🍔 Food
* 🚗 Transport
* 🛍️ Shopping
* 🧾 Bills
* 🎬 Entertainment
* ❤️ Health
* 📚 Education
* 💼 Salary
* 💻 Freelance
* 🎁 Gift
* 📌 Other

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Browser Local Storage

Everything is contained inside a **single `index.html` file**.

---

## 📁 Project Structure

```text
MoneyTrack/
│
└── index.html
```

There are no separate CSS or JavaScript files required.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### 2. Open the project

Go into the project directory:

```bash
cd your-repository
```

### 3. Open the website

Simply open:

```text
index.html
```

in your browser.

No server, database, Node.js, or additional setup is required.

---

## 💾 Data Storage

MoneyTrack uses the browser's **localStorage** to save transactions.

This means:

* Your transactions remain after refreshing the page.
* No database is required.
* No backend server is required.
* Data is stored locally in your browser.

> Clearing your browser's site data can remove locally stored transactions.

---

## 📊 Dashboard

The dashboard provides three important financial values:

### Total Income

Shows the total amount of money received.

### Total Expenses

Shows the total amount spent.

### Available Balance

Shows the amount remaining after expenses:

```text
Income - Expenses
```

---

## 🎯 Purpose

MoneyTrack was created as a lightweight way to manage everyday personal finances without requiring an account, backend server, or database.

It is suitable for tracking:

* Daily spending
* Monthly expenses
* Personal income
* Shopping expenses
* Food expenses
* Bills
* Transportation
* Freelance income
* Other personal transactions

---

## 🔮 Future Improvements

Possible future improvements include:

* 📅 Monthly financial reports
* 📊 Advanced charts and graphs
* 🔍 Transaction search
* ✏️ Edit transactions
* 📆 Date-range filtering
* 📤 Export transactions to CSV
* 📥 Import financial data
* 🌙 Dark mode
* 🎯 Monthly spending limits
* 🔔 Budget notifications
* 📱 Progressive Web App support
* 🔐 Optional PIN/password protection

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Test the application
5. Commit your changes
6. Push your branch
7. Create a Pull Request

---

## 📜 License

This project is open for learning, personal use, and further development.

---

## 👨‍💻 Author

**Atharva A. Deshmukh**

---

⭐ If you find this project useful, consider giving the repository a star!

---

© 2026 Atharva A. Deshmukh. All Rights Reserved.

```
```
