# Crossword Game

A desktop crossword game developed in **Python** with a graphical user interface. The application supports **1–4 players**, user accounts, multiple game modes, and persistent data storage using an ORM. The project follows good programming practices and includes automatically generated documentation in PDF format.

---

## Features

### 🖥️ Graphical User Interface

A user-friendly GUI built for intuitive gameplay and navigation.

### 👤 Player Registration & Login

- Supports multiple player accounts
- Secure authentication
- Persistent player profiles

### ⚙️ Game Settings

Customize game options before starting a new session.

### 🗄️ Player Database

Player information is stored using an **ORM**, providing structured and secure data management.

### ❓ Questions & Answers Database

A dedicated database stores all crossword questions and corresponding answers.

### 🎮 Game Modes

The game includes two gameplay modes:

- Timed Mode
- First Mistake Mode

### 🏆 Score Tracking

Displays player scores during gameplay and presents final results at the end of each match.

### 📄 PDF Export

Game results can be exported as a **PDF report**.

### 🔒 Password Security

Player passwords are securely hashed using **SHA-256** before being stored in the database.

---

## Project Structure

```text
.
├── main.py                     # Application entry point
├── gui/                        # Graphical user interface
├── database/                   # ORM models and database logic
├── questions/                  # Crossword questions and answers
├── settings/                   # Game configuration
├── reports/                    # Generated PDF reports
├── assets/                     # Images and other resources
└── PPY_S30033_PROJECT.pdf      # Project documentation (Polish)
```

> *The exact project structure may vary depending on the implementation.*

---

## Documentation

The repository includes documentation written in **Polish**:

```text
PPY_S30033_PROJECT.pdf
```

This document contains a detailed description of the project, its architecture, implementation, and functionality.

---

## Technologies

- Python
- Tkinter (GUI)
- SQLite
- SQLAlchemy (ORM)
- SHA-256 Password Hashing
- PDF Report Generation

---

## Usage

Run the application:

```bash
python main.py
```

After launching the application you can:

1. Register or log in.
2. Configure the game settings.
3. Choose a game mode.
4. Play the crossword.
5. View and export the final results as a PDF report.
