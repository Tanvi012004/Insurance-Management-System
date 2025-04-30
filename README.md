# Insurance Management System :

A full-stack web application designed to manage insurance operations such as policy creation, claim filing, and user account management. The system provides a secure and user-friendly interface for users to handle their insurance details efficiently.

🛠️ Technologies Used :

- Frontend: HTML5, CSS3, JavaScript
- Backend: Python, Flask
- Database: PostgreSQL

🚀 Features :

- User Registration & Login
- Add and View Insurance Policies
- File Insurance Claims
- View Filed Claims

📦 Project Setup and Run Instructions: 

Follow these steps to run the project locally:
1. Clone the Repository

git clone https://github.com/your-username/insurance-management-system.git
cd insurance-management-system

2. Create and Activate a Virtual Environment

- For Windows
python -m venv venv
venv\Scripts\activate

- For Mac/Linux
python3 -m venv venv
source venv/bin/activate

3. Install Dependencies:

pip install -r requirements.txt
If there's no requirements.txt, you can manually install:
pip install flask psycopg2-binary sqlalchemy

4. Configure the Database:

- Make sure PostgreSQL is installed and running.
- Create a PostgreSQL database:

CREATE DATABASE insurance_db;

Update your app.py or config.py file with your database URI:
SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@localhost/insurance_db'

Replace username, password, and insurance_db as per your setup.

5. Run the Flask Application:

- For Windows
set FLASK_APP=app.py
set FLASK_ENV=development
flask run

- For Mac/Linux
export FLASK_APP=app.py
export FLASK_ENV=development
flask run

The application will be accessible at https://insurance-management-system-hdqa.onrender.com/

Screenshots:

![image1](https://github.com/user-attachments/assets/e04b2faf-63d7-4be5-bfb9-857e50f67d9b)
![image2](https://github.com/user-attachments/assets/c7787d19-6239-45de-bb45-999ed827ef8c)
![image3](https://github.com/user-attachments/assets/150e4ce4-968c-4f92-98b2-bd10d6a835df)
![image4](https://github.com/user-attachments/assets/49599951-1788-43d3-8e81-91b10afa6030)
![image5](https://github.com/user-attachments/assets/a61d46f2-8948-42a7-8df0-eaf89c7f70bf)
![image6](https://github.com/user-attachments/assets/d86935ed-7d23-419a-b5c0-bb59b44b6a0d)
![image7](https://github.com/user-attachments/assets/71e411ae-c25c-41fb-97e8-bc1c9fdbd1fd)
