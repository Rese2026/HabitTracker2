# 🗓️ Python Habit Tracker 

A simple, command-line habit tracking application built with Python. The application helps users build consistent routines by creating habits, tracking completions, monitoring streaks, and reviewing their progress.

## 📌 Project Overview

The Habit Tracker is a Python-based CLI application designed to make habit tracking straightforward and accessible. Users can manage daily and weekly habits, record completed activities, and keep track of their consistency over time.

The application stores data locally using CSV files, allowing habits and completion records to persist between sessions.

## 🔨 Installation and running

1. Download/extract the project ZIP into a folder, keeping `habit_tracker.py`, `analytics.py`, `tests/`, and `fixtures/` together.
2. Open a terminal in the extracted `habit_tracker_submission` folder.
3. Check Python: `python --version` (use `python3 --version` if necessary).
4. Start: `python habit_tracker.py` (or `python3 habit_tracker.py`).
5. Choose **7. Load five example habits** to import the sample dataset, or **2. Create habit** to start with your own habits. The sample import works only when your habit list is empty.
6. Choose **3. Complete habit** to record the current date **and time**; choose **6. Analyse habits** for all required analytics. Choose **8. Exit** to close the app.

## ✨ Features

- **Create habits** – Add habits with a title, description, and frequency.
- **Track completion** – Mark habits as completed and record completion dates.
- **View habits** – Display your current habits.
- **Edit habits** – Modify existing habit details.
- **Delete habits** – Remove habits you no longer want to track.
- **Progress summary** – Review your habit progress.
- **Streak tracking** – Calculate consecutive completion periods.
- **CSV persistence** – Save and load habit data locally.
- **Input validation** – Handle invalid inputs and prevent common errors.
- **Unit testing** – Test core functionality and application logic.

## 🛠️ Technologies Used

- **Python 3**
- **CSV** – Local data storage
- **UUID** – Unique habit identifiers
- **Unittest** – Testing framework

## 🧠 Technical Approach

The application follows a modular, object-oriented approach, separating responsibilities into different components:

- **Habit** – Represents an individual habit and its data.
- **HabitService** – Handles the core application logic and habit management.
- **HabitRepository** – Manages CSV-based data storage and retrieval.
- **HabitCLI** – Provides the user interface through the terminal.

This separation helps improve readability, maintainability, and testability.


## 🎓 Project Context

This project was developed as a Python programming project to practice object-oriented programming, functional concepts, file handling, validation, error handling, and unit testing.

