Insurance Management System :

A full-stack web application designed to manage insurance operations such as policy creation, claim filing, and user account management. The system provides a secure and user-friendly interface for users to handle their insurance details efficiently.

🛠️ Technologies Used

Frontend: HTML5, CSS3, JavaScript
Backend: Python, Flask
Database: PostgreSQL

🚀 Features

User Registration & Login
Add and View Insurance Policies
File Insurance Claims
View Filed Claims

📦 Project Setup and Run Instructions

Follow these steps to run the project locally:
1. Clone the Repository

git clone https://github.com/your-username/insurance-management-system.git
cd insurance-management-system

2. Create and Activate a Virtual Environment

# For Windows
python -m venv venv
venv\Scripts\activate

# For Mac/Linux
python3 -m venv venv
source venv/bin/activate

3. Install Dependencies

pip install -r requirements.txt
If there's no requirements.txt, you can manually install:
pip install flask psycopg2-binary sqlalchemy

4. Configure the Database

Make sure PostgreSQL is installed and running.
Create a PostgreSQL database:

CREATE DATABASE insurance_db;

Update your app.py or config.py file with your database URI:

SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@localhost/insurance_db'

Replace username, password, and insurance_db as per your setup.

5. Run the Flask Application

# For Windows
set FLASK_APP=app.py
set FLASK_ENV=development
flask run

# For Mac/Linux
export FLASK_APP=app.py
export FLASK_ENV=development
flask run

The application will be accessible at https://insurance-management-system-hdqa.onrender.com/








