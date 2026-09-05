# Bank Transaction Ledger

 A simple, responsive, browser-based **bank transaction ledger** built with a single HTML file. Track income, expenses, running balances, categories, and accounts without installing any software.

 ## Features

 - Add bank transactions
- Edit existing transactions
- Delete transactions
- Track **income/deposits** and **expenses/withdrawals**
- Automatic running balance
- Total income calculation
- Total expense calculation
- Current balance display
- Transaction count
- Search transactions
- Filter by transaction type
- Filter by category
- Add optional notes
- Export transactions to CSV
- Data automatically saved in browser `localStorage`
- Responsive design for desktop, tablet, and mobile
- No external libraries or dependencies

 ## Screenshot

 Add a screenshot of your ledger here:

```
![Bank Transaction Ledger](screenshot.png)
```

 ## Getting Started

 ### Option 1 — Run Locally

 No server or installation is required.

 1. Download `index.html`.
2. Double-click the file.
3. It will open in your web browser.
4. Start adding transactions.

 ### Option 2 — GitHub Pages

 You can host the ledger for free using GitHub Pages.

 1. Create a new GitHub repository.
2. Upload `index.html`.
3. Go to **Settings → Pages**.
4. Select your main branch as the deployment source.
5. Save the settings.
6. GitHub will provide a public website URL.

 ## Usage

 Click **\+ Add Transaction** to create a new ledger entry.

 Each transaction contains:

 | Field | Description |
| --- | --- |
| Date | Transaction date |
| Type | Deposit/income or withdrawal/expense |
| Description | Description of the transaction |
| Category | Transaction category |
| Account | Bank account associated with the transaction |
| Amount | Transaction amount |
| Notes | Optional additional information |

 The ledger automatically calculates the running balance based on the transaction date.

 ## Data Storage

 This application uses the browser's **localStorage** to save transactions.

 That means:

 - No database is required.
- No account is required.
- Data remains available when you close and reopen the browser.
- Data is specific to the browser/device being used.
- Clearing browser storage can delete your ledger data.
- Transactions are **not automatically synchronized between devices**.

 ### Important

 This project is intended as a personal bookkeeping/ledger tool. It should **not be considered a secure banking application** or a replacement for your bank's official records.

 Avoid entering sensitive information such as:

 - Bank account numbers
- Debit/credit card numbers
- Passwords
- PINs
- Social Security numbers
- Online banking credentials

 ## CSV Export

 Use the **Export CSV** button to download your transactions.

 The exported file contains:

```
Date
Type
Description
Category
Account
Amount
Notes
```

 The CSV can be opened with applications such as Microsoft Excel, Google Sheets, or LibreOffice Calc.

 ## Project Structure

 This project intentionally uses a single HTML file:

```
bank-ledger/
└── index.html
```

 The HTML file contains:

 - HTML structure
- CSS styling
- JavaScript functionality
- Local storage functionality
- CSV export functionality

 No build process is required.

 ## Technologies

 - HTML5
- CSS3
- Vanilla JavaScript
- Browser Local Storage
- CSV

 No frameworks or external dependencies are required.

 ## Customization

 You can modify the CSS variables near the beginning of the file to change the color scheme:

```
:root {
  --bg: #f5f7fb;
  --card: #fff;
  --text: #172033;
  --primary: #2563eb;
  --green: #16834b;
  --red: #dc2626;
}
```

 You can also add additional categories to the `<datalist>` in `index.html`.

 ## Roadmap

 Potential future improvements:

 - [ ] Multiple bank accounts
- [ ] Account-specific balances
- [ ] Monthly summaries
- [ ] Income/expense charts
- [ ] Date-range filtering
- [ ] Recurring transactions
- [ ] Import transactions from CSV
- [ ] Backup and restore
- [ ] Cloud database synchronization
- [ ] User authentication
- [ ] Dark mode
- [ ] Printable reports
- [ ] Budget tracking

 ## Contributing

 Contributions and improvements are welcome.

 1. Fork the repository.
2. Create a new branch:

```
git checkout -b feature/my-improvement
```

 3. Make your changes.
4. Commit your changes:

```
git commit -m "Add my improvement"
```

 5. Push the branch:

```
git push origin feature/my-improvement
```

 6. Open a Pull Request.

 ## License

 This project is provided for personal and educational use. You are free to modify it for your own needs.

---

 ### Quick Start

```
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

 Then open `index.html` in your browser.

 **That's it — no installation, server, database, or build process required.**
