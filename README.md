# 📝 Flask Blog Application

Welcome to the **Flask Blog Application**! This project is a web-based blogging platform developed using Python's Flask framework. It allows users to register, log in, create posts, and interact with other users' content.

## 🌟 Features

- **User Authentication**: Secure registration and login functionality.
- **Create, Read, Update, Delete (CRUD) Posts**: Users can manage their blog posts.
- **Profile Management**: Update profile information and profile pictures.
- **Password Reset**: Reset passwords securely via email.

## 🛠️ Technologies Used

- **Backend**: Flask, Flask SQLAlchemy, Flask Login, Flask WTF
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default), can be configured to use PostgreSQL or MySQL
- **Other**: Pillow for image processing, Flask Mail for email support

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- Python 3.6 or higher
- Virtual environment tool (optional but recommended)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Nikhil-Rao20/socialmedia_project.git
   cd socialmedia_project
   
2. **Create a virtual environment (optional):**:

      ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate


3. **Install the required packages:**

     ```bash
       pip install -r requirements.txt


---

### Configuration

1. **Set up environment variables**:
   Create a .env file in the project root directory and add the following:

   ```bash
   SECRET_KEY='your_secret_key'
   SQLALCHEMY_DATABASE_URI='sqlite:///site.db'  # or your preferred database URI
   MAIL_SERVER='smtp.googlemail.com'
   MAIL_PORT=587
   MAIL_USE_TLS=True
   MAIL_USERNAME='your_email@example.com'
   MAIL_PASSWORD='your_email_password'
  
Replace `your_secret_key`, `your_email@example.com`, and `your_email_password` with your actual credentials.
   
3. **Initialize the database:**:

      ```bash
   flask db init
   flask db migrate -m "Initial migration."
   flask db upgrade



### Running the Application


1. **Set the Flask app environment variable:**:

   ```bash
   export FLASK_APP=run.py  # On Windows: set FLASK_APP=run.py
   export FLASK_ENV=development  # Enables debug mode

   
2. **Run the Flask application:**:

      ```bash
   flask run


The application will be accessible at http://127.0.0.1:5000/.


## 📂 Project Structure

## 🧪 Testing

To run the test suite:

      ```bash
   pytest


Ensure you have pytest installed in your environment.


## 📧 Contact
For any inquiries or feedback, please contact nikhil01446@gmail.com


## 💡Inspiration

This project was developed following Corey Schafer's Flask tutorial series. For more detailed explanations and tutorials, refer to his [YouTube playlist](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH).

