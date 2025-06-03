# Flask Blog Practice

A personal blog application built with Flask, HTML templates, and Bootstrap. This project is part of a learning exercise and demonstrates how to:

- Render blog posts from an API
- Use Flask routing and templates
- Handle form submissions
- Send emails using Python's `smtplib`
- Organize static assets and templates

---


### Prerequisites

- Python 3.10+
- `pip` installed

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ajs2583/flask_blog_practice.git
cd flask_blog_practice
```
2. Create Virtual Enviroment
```bash
python -m venv venv
source venv/bin/activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Set up the .env file with your email credentials:
```bash
MY_EMAIL=your_email@example.com
PASSWORD=your_email_password
```
5. Run the app
```bash
python app/main.py
```
### Contact Form
Messages submitted through the Contact form are sent to your email using the SMTP protocol. Make sure to allow less secure apps if using Gmail (or use an app-specific password).
