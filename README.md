# Email-System-Console-based
A simple Java console-based Email System where users can compose, send, view, and delete emails. All data is stored in a local text file using File I/O. This project demonstrates OOP concepts, layered architecture, and basic CRUD operations in Java.

# 📁 Project Structure

EmailSystem/
│
├── EmailSystem.java         # Main class (entry point)
├── Email.java               # Model class
├── EmailDAO.java            # Data Access Object (File I/O handling)
├── EmailService.java        # Business logic
├── emails.txt               # Email storage file (auto-created)
├── README.md                # Project documentation
└── images/                  # Screenshots (optional)
# HOW TO RUN

# 🔧 Requirements
Java JDK 8 or later
Any Java IDE (VS Code / IntelliJ / Eclipse) or
Terminal + Text Editor (Notepad++, Sublime, etc.)
# Steps :
1. Open the project folderin VS code.
2. Press F5 or click Run>start Debugging.
3. Select configuration: Main.
4. Use number options in the terminal to interact with the menu.


# 🧩 Features
Feature	Description
✅ Send Email	          Compose and send email with subject and body
📩 View Emails        	View all sent and received emails
📥 View Inbox	          View only received emails (receiver mailbox)
🗑️ Delete Email       	Delete email using sender, receiver, and subject
💾 File I/O           	Uses a text file (emails.txt) for persistent storage
🔐 Input Validation   	Basic validation on inputs like email format and empty fields

# 🏗️ Project Architecture

+----------------------+
|     EmailSystem      | <-- Main (UI + Menu)
+----------------------+
           |
           ↓
+----------------------+
|    EmailService      | <-- Logic Layer
+----------------------+
           |
           ↓
+----------------------+
|      EmailDAO        | <-- File I/O
+----------------------+
           |
           ↓
+----------------------+
|       Email          | <-- Model
+----------------------+

