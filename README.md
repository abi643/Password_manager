# 🔐 Password Manager (CLI - Python)

A command-line based password manager built in Python that securely stores user credentials using AES encryption.
This project demonstrates practical implementation of cryptography, secure key derivation, and file handling.

---

## 🚀 Features

* 🔑 Secure encryption using AES (CBC mode)
* 🧂 Key derivation using PBKDF2 with random salt
* 🔐 Password-protected database access
* ➕ Add new credentials (username/email, password, platform)
* ✏️ Edit and delete stored credentials
* 🔎 Display credentials in a structured table format
* 🔄 Generate strong random passwords
* 💾 Backup database functionality
* 🗑️ Option to erase database securely

---

## 🛠️ Technologies Used

* Python 3
* PyCryptodome (AES encryption)
* Tabulate (CLI table formatting)

---

## 📦 Installation

1. Clone the repository:

```
git clone https://github.com/YOUR_USERNAME/password-manager.git
cd password-manager
```

2. Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the program:

```
python password_manager.py
```

* On first run, a database file (`passwords.db`) will be created automatically.
* Default password:

```
password123
```

⚠️ Change this immediately after first login.

---

## 📁 Project Structure

```
password-manager/
│── password_manager.py
│── requirements.txt
│── README.md
│── .gitignore
```

---

## 🔒 Security Notes

* Uses PBKDF2 for secure key derivation
* Each database uses a unique random salt
* AES encryption uses a random IV for every save
* Database file is encrypted and not human-readable

⚠️ This is a learning project and not recommended for production use.

---

## 🚫 Ignored Files

The following files are excluded using `.gitignore`:

```
*.db
*.bak
__pycache__/
```

---

## 📌 Future Improvements

* Switch to AES-GCM for authenticated encryption
* Implement Argon2 for stronger key derivation
* Add GUI interface (Tkinter / PyQt)
* Add search and filtering functionality
* Improve input validation and error handling

---

## 👨‍💻 Author

**Abid Shafique**
Computer Science Student
