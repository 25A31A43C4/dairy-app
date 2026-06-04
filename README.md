Diary App

A simple command-line diary application written in C++. Users can create diary entries and view previously saved entries. All entries are stored in a text file along with the date and time they were created.

Features
Write diary entries
Automatically save the current date and time
View all saved entries
Persistent storage using a text file
Simple menu-driven interface
Requirements
C++ compiler with C++11 support or later
Build

Using g++:

g++ main.cpp -o diary
Run

Linux/macOS:

./diary

Windows:

diary.exe
Usage
==== MY DIARY ====

1. Write Entry
2. View Entries
3. Exit
Write Entry

Select option 1 and enter your diary entry.

Write your diary entry:
Today I started learning C++.
View Entries

Select option 2 to display all saved diary entries.

Date: Thu Jun  4 20:15:00 2026

Today I started learning C++.
File Storage

Diary entries are stored in:

diary.txt

Each entry contains:

Date and time
Entry content
Project Structure
DiaryApp/
│
├── main.cpp
├── diary.txt
└── README.md
Future Improvements
Multi-line diary entries
Search entries by keyword
Search entries by date
Delete entries
Edit entries
Password protection
Mood tracking
Export and backup functionality
