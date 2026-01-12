# Habit-Tracker-App---TrackYoHab
A very basic habit tracking app that runs in the Python interpreter using a command line interface

TrackYoHab - Minimalist Habit Tracker

TrackYoHab is a minimal, lightweight, backend-focused Python application designed to help users define, track, and analyze their habits through a Command Line Interface (CLI).

Prerequisites
Please ensure you have the following installed on your system:
Python 3.10 or later (Supports modern type hinting and f-strings).
A Terminal or Command Prompt (to run the application).
No external libraries (like pandas or requests) are required; the app runs entirely on the Python Standard Library.

Installation
1. Create a Project Folder:
Open your terminal and create a directory for the project.

3. Create the Python File:
Create a file named main.py and paste the Python code provided in the previous response into this file.
To start the habit tracker, just run the code in your terminal
On the first launch the app automatically generates a file named habits.json in your folder. This file stores your data and allows you to resume your progress in future sessions.


Usage Guide

Predefined Habits

The app starts with 5 built-in basic habits to give users an overview of possible options:
Daily: Brush Teeth, Go to Gym
Weekly: Laundry
Monthly: Pay Rent
Yearly: Dentist Visit
Creating a New Habit
Select Option 2 from the main menu.
Enter a descriptive name (e.g., "Read 20 Pages").
Assign a periodicity by typing: daily, weekly, monthly, or yearly.

Checking Off a Task

Select Option 3 from the main menu.
Type the name of the habit (case-insensitive).
The app records the exact timestamp of completion. If you complete the task within its period (e.g., once every 24 hours for daily habits) your streak continues.

Analyzing Streaks

1. Select Option 4 from the main menu.
2. The app will display:
The Longest Streak Overall (the highest number achieved across any habit).
A breakdown of individual streaks for every habit you are tracking.

Data Persistence

You do not need to manually save. Every time you add, delete, or check off a habit, the habits.json file is updated automatically.
You can safely exit the app (Option 6) and return later without losing data.

File Structure

main.py: The core application logic (OOP classes and Functional Analytics).
habits.json: Used to store your habits and completion timestamps.

Troubleshooting

Habit Not Found: Ensure you type the name exactly as it appears in the "View All Habits" list.
JSON Errors: If you manually edit habits.json and the app fails to start, delete the habits.json file to reset the application to its default state.
