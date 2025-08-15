# WalletWatch 

A modern expense tracking application built with React. Easily manage your income and expenses, visualize your spending, and generate insightful reports.

## Features

- **Dashboard**: View your current balance, total income, and total expenses.
- **Add Transaction**: Quickly add income or expense transactions with category, description, and date.
- **Transaction List**: See all your transactions, edit or delete them as needed.
- **Reports**: Filter transactions by month, view category-wise breakdowns, and compare income vs expenses with charts.
- **Charts**: Interactive bar and pie charts powered by Chart.js.
- **Motivational Quotes**: Get a random motivational quote to inspire your financial journey.
- **Reset Data**: Easily reset all your data to start fresh.

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/WalletWatch.git
   cd WalletWatch
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- Use the navigation bar to switch between Dashboard, Transactions, and Reports.
- Add new transactions using the "+ Add Transaction" button.
- Edit or delete transactions from the Transactions page.
- View monthly reports and charts in the Reports section.
- Click "Get Quote" for a motivational quote.
- Use "Reset" to clear all data.

## Technologies Used

- React
- React Router
- Chart.js & react-chartjs-2
- CSS

## Folder Structure

```
src/
  Components/
    Navbar.js
    TransactionCards.js
    RecentTransactions.js
    NoTransactions.js
  Pages/
    Dashboard.js
    Transaction.js
    Report.js
    AddTransaction.js
    NotFound.js
  styles/
    Dashboard.css
    Transaction.css
    Report.css
    AddTransaction.css
    Navbar.css
    NoTransactions.css
  App.js
  index.js
  ...
```


**Enjoy tracking your expenses and improving your
