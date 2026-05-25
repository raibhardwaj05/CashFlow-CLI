# CLI Expense Tracker

A terminal-based Expense Tracker application built using Python.

This project helps users:

* manage monthly budgets
* track expenses
* analyze spending habits
* filter expense records
* visualize expense data

The project was built as part of a practical learning journey focused on improving:

* backend thinking
* project structuring
* debugging ability
* modular programming
* problem-solving

---

# Features

## Budget Management

* Set monthly budget
* Track remaining balance
* Negative balance support when overspending
* Budget alerts

---

## Expense Management

* Add expenses
* Category-based expense tracking
* Payment mode support
* Expense history display

---

## Dynamic Category Handling

* Users can organize expenses using multiple predefined categories covering a wide range of daily spending types
* Structured category selection helps maintain cleaner and more organized expense records


---

## Filtering System

Filter expenses using:

* category
* payment mode
* date/month/year

---

## Analytics & Visualization

Expense analysis using charts and plots.

Implemented using:

* Matplotlib
* Seaborn

---

## Error Handling

Robust validation system to prevent crashes from:

* invalid inputs
* wrong menu choices
* empty values
* unexpected user actions

The application allows users to re-enter values instead of terminating abruptly.

---

## Clean CLI User Interface

Implemented using PrettyTable for:

* formatted tables
* better readability
* structured terminal output

---

# Tech Stack

* Python
* JSON
* PrettyTable
* Matplotlib
* Seaborn
* Questionary

---

# Project Structure

```text
CLI-Expense-Tracker/
│
├── main.py
├── analyse.py
├── filter.py
├── helper_fun.py
├── load_data.py
├── store_data.py
├── data.json
├── requirements.txt
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/raibhardwaj05/CLI-Expense-Tracker.git
```

---

## Move Into Project Folder

```bash
cd CLI-Expense-Tracker
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

# Run Application

```bash
python main.py
```

---

# Executable Version

The project can also be converted into a standalone executable using PyInstaller.

Example:

```bash
pyinstaller --onefile main.py
```

---

# Future Improvements

Possible future upgrades:

* SQLite database integration
* FastAPI backend version
* Authentication system
* Expense editing
* Expense archiving system
* Better category normalization
* Export reports

---

# What I Learned From This Project

Through this project I practiced:

* modular programming
* project architecture
* JSON data handling
* debugging
* edge-case handling
* CLI application flow
* data visualization
* filtering logic
* validation systems

---

# Screenshots

Add screenshots of:

* CLI menu
* expense tables
* analytics plots

inside this section later.

---

# Author

Bhardwaj Rai
