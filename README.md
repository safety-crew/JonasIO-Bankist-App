# Bankist

Bankist is a simple banking web application built with vanilla JavaScript, HTML, and CSS. It is designed as a learning project to practice and demonstrate the use of JavaScript array methods and DOM manipulation.

## Features

- **Login System:** Users can log in using a username (generated from their name) and a PIN.
- **View Balance:** Displays the current account balance.
- **View Movements:** Shows a list of deposit and withdrawal transactions.
- **Transfer Money:** Allows users to transfer money to other accounts.
- **Request Loan:** Users can request a loan if they have a deposit of at least 10% of the requested amount.
- **Close Account:** Users can close their account by confirming their username and PIN.
- **Sort Transactions:** Transactions can be sorted in ascending order.
- **Summary Section:** Displays total deposits, withdrawals, and interest earned.
- **Logout Timer:** Shows a timer for automatic logout (UI only).

## Technologies Used

- **JavaScript:** Main application logic and array method practice ([script.js](script.js))
- **HTML:** Structure of the app ([index.html](index.html))
- **CSS:** Styling and layout ([style.css](style.css))

## How It Works

1. **Accounts Data:** Four sample accounts are defined in [`script.js`](script.js) with owner names, movements (transactions), interest rates, and PINs.
2. **Username Generation:** Usernames are automatically generated from the initials of the account owner's name.
3. **UI Updates:** All UI updates (balance, movements, summary) are handled by functions using array methods like `map`, `filter`, `reduce`, and `find`.
4. **Event Handling:** Button clicks for login, transfer, loan, close account, and sorting are handled with event listeners.

## Learning Focus

This project is intended to help learners understand and practice:

- Array methods: `map`, `filter`, `reduce`, `find`, `forEach`, `some`, `every`, `sort`, and more.
- DOM manipulation and event handling.
- Basic state management in a single-page application.

## Getting Started

1. Clone or download the repository.
2. Open [`index.html`](index.html) in your browser.
3. Use one of the sample accounts to log in:

| Owner                   | Username | PIN   |
|-------------------------|----------|-------|
| Jonas Schmedtmann       | js       | 1111  |
| Jessica Davis           | jd       | 2222  |
| Steven Thomas Williams  | stw      | 3333  |
| Sarah Smith             | ss       | 4444  |

## License

This project is for educational purposes only.

---

**Files:**
- [index.html](index.html)
- [style.css](style.css)
- [script.js](script.js)
