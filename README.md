🔐 MyPass – Password Manager (Python + Tkinter)

MyPass is a simple and lightweight desktop password manager built using Python and Tkinter.
It allows users to generate strong passwords, securely store credentials locally, and quickly retrieve saved login details through a clean graphical interface.

📸 Screenshots
🖥️ Application Interface

🔒 Logo

🚀 Features

🔑 Strong random password generator

📋 Automatically copies generated password to clipboard

💾 Stores credentials locally in password.json

🔍 Search functionality to retrieve saved credentials

🖥️ Simple and user-friendly GUI

📦 Lightweight and easy to run

🛠️ Tech Stack

Python 3

Tkinter – GUI framework

JSON – Local storage format

Pyperclip – Clipboard functionality

Random module – Password generation

📂 Project Structure
MyPass/
│── main.py
│── password.json   (auto-created after first save)
│── logo.png
│── passwordmanager.png
│── README.md
⚙️ How It Works
🔐 Password Generation

Generates 8–10 random letters

Adds 2–4 symbols

Adds 2–4 numbers

Shuffles characters for better randomness

Automatically copies password to clipboard

💾 Saving Credentials

Enter Website, Email/Username, and Password

Data is stored in structured JSON format:

{
    "example.com": {
        "email": "example@gmail.com",
        "password": "GeneratedPassword123!"
    }
}
🔎 Search Function

Enter website name

Retrieves stored email and password

Automatically copies password to clipboard

🖥️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/mypass-password-manager.git
cd mypass-password-manager
2️⃣ Install Required Package
pip install pyperclip
3️⃣ Run the Application
python main.py
📌 Requirements

Python 3.x installed

pip package manager

🔒 Security Note

This project stores passwords locally in a JSON file without encryption.
It is intended for educational purposes. For production use, encryption and master authentication should be implemented.

