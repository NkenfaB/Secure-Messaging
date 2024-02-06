Public Key Authentication System with RSA Algorithm
Project Description
This project is a secure messaging web application that allows users to send encrypted messages to each other. The application uses Flask as the web framework and SQLite for database storage. The messaging functionality is secured using asymmetric encryption and digital signatures.

Features
User registration and login with password hashing
Asymmetric encryption and digital signatures for secure messaging
Certificate-based authentication
User-friendly web interface for sending and receiving messages
Secure storage of private keys and certificates
SSL/TLS encryption for secure communication
Installation and Usage Guide
Prerequisites
Python 3.x installed on your system
Git installed on your system (optional, for cloning the repository)
Installation Steps
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/NkenfaB/Secure-Messaging.git
Alternatively, you can download the repository as a ZIP file and extract it.

Navigate to the project directory:

bash
Copy code
cd Secure-Messaging
(Optional) Create and activate a virtual environment to isolate project dependencies:

bash
Copy code
python -m venv venv
On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install the required Python packages using pip and the requirements.txt file:

bash
Copy code
pip install -r requirements.txt
Running the Application
Run the Flask web application:

bash
Copy code
python app.py
Access the application in your web browser by visiting:

arduino
Copy code
http://127.0.0.1:5000/
Usage
Register a new user account if it's your first time using the application.
Log in using your credentials.
Send encrypted messages to other registered users.
Receive encrypted messages sent to your account.
Note
Make sure to log out of your account when you're done using the application.
