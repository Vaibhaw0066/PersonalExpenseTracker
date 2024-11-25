# Expense Tracker Application

A **web-based expense tracker** that helps users manage their personal expenses effectively. Users can track their spending, categorize expenses, and view a detailed list of transactions with timestamps. This application includes dynamic UI updates, date formatting, and easy interaction to add or delete expenses.

---

## Features

- **Dynamic Expense Listing**: Displays a real-time list of expenses.
- **Custom Date Formatting**: Dates are shown in the format `yyyy-MM-dd HH:mm:ss`.
- **Interactive Delete Functionality**: Users can delete individual expense items.
- **Optimized UI Updates**: Supports appending new expenses or refreshing the list.

---

## Tech Stack

- **Frontend**:
  - **HTML**: For structuring the expense list and creating the UI.
  - **CSS**: For styling the user interface, ensuring a responsive and visually appealing design.
  - **JavaScript**: For dynamic rendering of expense items and handling interactivity (such as deleting items).

- **Backend**:
  - **Node.js** (Optional): For a simple backend to manage expense data (if used for persistence).
  - **Express** (Optional): A minimal web framework for handling API requests (if used for API integration).

- **Database** (Optional):
  - **MongoDB** (Optional): For storing expense records if the backend is implemented. Alternatively, data can be kept in memory for a simpler setup.

---

## API Details

### 1. **Get All Expenses**

**Endpoint**: `GET /api/expenses`

**Description**: Retrieves a list of all the expenses.

**Response**:
```json
[
  {
    "id": 1,
    "description": "Coffee",
    "amount": 5.5,
    "category": "Food",
    "date": "2024-11-07T00:00:00.000+00:00"
  },
  {
    "id": 2,
    "description": "Train Ticket",
    "amount": 15.0,
    "category": "Transport",
    "date": "2024-11-07T12:30:00.000+00:00"
  }
]
