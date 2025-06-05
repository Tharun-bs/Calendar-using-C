# 📅 Console-Based Calendar in C

A colorful and interactive terminal-based calendar application written in C. It highlights today’s date, past dates in red, and future dates in yellow. The program can display the full calendar for any given year, using system time to highlight the current day.

---

## ✅ Features

- Displays the calendar of any given year
- Automatically highlights:
  - ✅ **Today’s date** in green
  - 🔴 **Past dates** in red
  - 🟡 **Future dates** in yellow
- Uses system time for automatic date detection
- Leap year handling included
- Custom terminal coloring using ANSI escape codes

---

## 🧠 How It Works

- Uses C standard libraries like `<stdio.h>`, `<stdlib.h>`, and `<time.h>`
- Calculates the starting weekday of the year using Zeller’s congruence logic
- Adjusts February for leap years
- Prints each month with proper alignment based on the weekday

---

## 💻 Requirements

- C Compiler (like `gcc`)
- Unix/Linux/macOS Terminal or Windows Terminal with ANSI color support

---

## 🚀 Usage

### 🔧 Compile the code:
```bash
gcc -o calendar calendar.c
