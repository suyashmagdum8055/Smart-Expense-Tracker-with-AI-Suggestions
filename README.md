# Smart Expense Tracker with AI-Powered Financial Insights

## Overview

Smart Expense Tracker is a full-stack web application designed to help users manage their personal finances efficiently. The system allows users to record income and expenses, analyze spending patterns through an interactive dashboard, and receive AI-powered financial suggestions to improve budgeting and savings habits.

The application combines financial tracking, data visualization, and intelligent recommendations to provide users with actionable insights into their financial behavior.

---

## Features

### Expense Management
- Add, edit, and delete expenses
- Track income and expenditures
- Categorize transactions
- View transaction history
- Filter records by category and date

### Dashboard & Analytics
- Monthly expense summary
- Income vs Expense analysis
- Category-wise spending distribution
- Financial overview cards
- Interactive charts and graphs

### AI-Based Suggestions
- Personalized spending recommendations
- Budget optimization insights
- Overspending detection
- Savings improvement suggestions
- Monthly financial health analysis

### User Authentication
- User registration
- Secure login system
- Session management
- Password protection

### Responsive Interface
- Mobile-friendly design
- Modern user interface
- Cross-device compatibility

---

## Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- PostgreSQL

### AI Module
- Rule-Based Recommendation Engine
- Spending Pattern Analysis
- Financial Insight Generation

---

## System Architecture

```text
User Interface (HTML, CSS, JavaScript)
                │
                ▼
         Flask Backend
                │
                ▼
        PostgreSQL Database
                │
                ▼
     AI Recommendation Engine
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Smart-Expense-Tracker.git

cd Smart-Expense-Tracker
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure PostgreSQL

Create a PostgreSQL database:

```sql
CREATE DATABASE expense_tracker;
```

Update database credentials inside the configuration file.

### Run the Application

```bash
python app.py
```

Application will run at:

```text
http://127.0.0.1:5000
```

---

## AI Recommendation Examples

### Example 1

Input:

```text
Monthly Income: ₹40,000
Food Expenses: ₹15,000
```

Output:

```text
Food expenses account for 37.5% of your income.
Consider reducing restaurant spending to increase monthly savings.
```

### Example 2

Input:

```text
Shopping expenses increased by 25% this month.
```

Output:

```text
Your shopping expenses have increased significantly compared to the previous month.
Consider setting a fixed shopping budget.
```

---

## Dashboard Insights

The dashboard provides:

- Total Income
- Total Expenses
- Remaining Balance
- Category-wise Expense Distribution
- Monthly Spending Trends
- AI Financial Suggestions

---

## Future Enhancements

- Machine Learning-based Expense Prediction
- AI Financial Chatbot
- OCR-Based Receipt Scanner
- PDF and Excel Report Export
- Email Notifications
- Budget Planning Module
- Multi-Currency Support
- Dark Mode Interface
- Cloud Deployment

---

## Learning Outcomes

This project demonstrates practical implementation of:

- Full Stack Web Development
- Flask Application Development
- PostgreSQL Database Management
- Data Visualization
- Financial Analytics
- AI-Based Recommendation Systems
- User Authentication and Authorization

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

Suyash Magdum


If you find this project useful, consider starring the repository.
