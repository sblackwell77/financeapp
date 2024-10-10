Finance Dashboard

A sleek, responsive Django-based web application that allows users to track their financial transactions (income and expenses) and check real-time stock prices. The project features a dark mode design for a modern and minimalistic user experience.

Features

Transaction Management: Add, view, and manage income and expenses with a simple and intuitive UI.
Stock Price Checker: Fetch real-time stock prices using an external API.
Dark Mode Design: Sleek, modern dark mode UI that enhances visual appeal and reduces eye strain.
Responsive Layout: Fully responsive design that works on both desktop and mobile devices.

Screenshots

Home/Transaction List
<img width="1440" alt="Screenshot 2024-10-10 at 12 04 08 AM" src="https://github.com/user-attachments/assets/aa10c9a2-5ec9-4357-89cc-c9c38180d6c6">

Add Transaction
<img width="1440" alt="Screenshot 2024-10-10 at 12 04 51 AM" src="https://github.com/user-attachments/assets/2623f0cd-e436-4e05-b64f-56bad4e5ce70">

Check Stock Prices
<img width="1440" alt="Screenshot 2024-10-10 at 12 05 12 AM" src="https://github.com/user-attachments/assets/9e8479d7-5ed5-4542-9be2-d900a023493f">


Technologies Used

Backend: Django
Frontend: HTML, CSS (Bootstrap), JavaScript
Database: SQLite (default Django database)
APIs: Alpha Vantage API for stock prices
Version Control: Git, GitHub

Set Up Instructions

Clone the repository:
git clone https://github.com/sblackwell77/financeapp.git
Navigate into the project directory:
cd finance_dashboard
Set up a virtual environment (optional but recommended):
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Apply migrations to set up the database:
python manage.py migrate
Run the development server:
python manage.py runserver
Access the app by navigating to http://127.0.0.1:8000/ in your browser.





