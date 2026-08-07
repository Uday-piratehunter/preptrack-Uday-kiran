# PrepTrack — Placement Preparation Performance Analyzer

## Project Overview

PrepTrack is a Python application that helps evaluate whether a student is ready for a placement mock interview. The program collects student details such as attendance, graduation year, project completion status, profile verification, and practice scores for seven days.

Based on the collected information, the application analyzes the student's performance by calculating the average score, classifying daily performance, checking eligibility conditions, and identifying any blockers. Finally, it generates a detailed report showing whether the student is ready for a mock interview along with the reason and the next action to take.

---

# Features Implemented

- Student profile input
- Student name validation
- Registration number validation
- Graduation year validation
- Attendance validation (0–100%)
- Yes/No validation for project completion
- Yes/No validation for profile verification
- Seven-day practice score processing
- Practice score validation (0–100 or -1 for absent)
- Absent day handling
- Score classification into:
  - Strong
  - Satisfactory
  - Needs Improvement
  - Critical
- Passed and failed day counting
- Highest score detection
- Lowest score detection
- First critical score detection
- Average score calculation
- Placement readiness evaluation
- Final report generation with primary blocker and next action

---

# Python Concepts Used

The application uses the following Python concepts:

- Variables
- Data Types (`int`, `float`, `str`, `bool`)
- Input and Output
- Type Casting
- Arithmetic Operators
- Comparison Operators
- Logical Operators
- Assignment Operators
- Conditional Statements (`if`, `elif`, `else`)
- `for` Loop
- `while` Loop
- `continue` Statement
- Boolean Values
- String Methods (`strip()`, `lower()`)
- Exception Handling (`try` and `except`)
- Formatted Strings (f-strings)

---

# How to Run the Program

Run the program using:

```bash
python main.py
```

If your system uses Python 3:

```bash
python3 main.py
```

Follow the instructions shown on the terminal and enter the required details. After entering all the inputs, the application will generate the final placement readiness report.

---

# Test Result Summary

The application was tested with different input combinations to verify that all validations and conditions work correctly.

### Test Cases

- Empty student name
- Empty registration number
- Invalid graduation year input
- Attendance below 0 or above 100
- Invalid Yes/No inputs
- Invalid practice scores
- Absent day using `-1`
- No practice attempts
- Student with critical score
- Student with fewer than six practice days
- Student with fewer than four passed days
- Student with average score below 70
- Student with attendance below 75%
- Student with incomplete project
- Student with unverified profile
- Student satisfying all eligibility conditions

### Result

All test cases were executed successfully. The application correctly validated user input, calculated performance, identified blockers, and generated the appropriate final status.

---

# Individual Contribution

**Name:**

T Uday Kiran

**Repository URL:**

https://github.com/Uday-piratehunter/preptrack-Uday-kiran

**My Main Contribution:**

I developed the complete PrepTrack application by implementing the input validation, score processing, placement eligibility logic, and final report generation. I also organized the code into different sections to make it easier to understand and maintain.

**Features I Implemented:**

- Student information collection
- Attendance validation
- Project completion validation
- Profile verification validation
- Seven-day practice processing
- Practice score validation
- Score classification
- Passed and failed day counting
- Highest and lowest score tracking
- Critical score detection
- Average score calculation
- Placement readiness evaluation
- Final report generation

**Python Concepts I Used:**

- Variables
- Loops (`for` and `while`)
- Conditional statements
- Boolean logic
- Exception handling
- Input validation
- Arithmetic and logical operators
- String methods
- f-strings
- `continue` statement

**Most Difficult Logic:**

The most challenging part was implementing the placement eligibility logic in the correct priority order. It also required careful handling of absent days while tracking the highest score, lowest score, and the first critical score.

**Problem I Faced:**

Initially, I found it difficult to calculate the average correctly when students were absent. I also needed to make sure that invalid inputs did not cause the program to stop unexpectedly.

**How I Solved It:**

I used `while` loops with `try` and `except` blocks for input validation. I handled absent days using the `continue` statement and maintained separate counters for attempted and absent days. This ensured that the calculations and final report were accurate.

---

# Code Review Completed

Yes, the code was reviewed after implementation.

The review focused on:

- Input validation
- Program logic
- Readability
- Variable naming
- Eligibility conditions
- Output formatting

The review confirmed that the application works correctly and the code is easy to understand.

---

# Feedback Received

The following feedback was received:

- Improve the readability of the final report.
- Validate every user input.
- Display the highest and lowest scores only when practice days are attempted.
- Make the eligibility logic easier to understand.
- Handle invalid inputs gracefully.

---

# Improvement Made After Review

Based on the review, I made the following improvements:

- Added complete input validation using `while` loops and exception handling.
- Improved the formatting of the final report.
- Added validation for Yes/No inputs.
- Prevented division-by-zero while calculating the average score.
- Displayed the highest and lowest scores only when valid practice scores exist.
- Added clear messages for the primary blocker and next action.
- Organized the code into separate sections with comments to improve readability.

---

# Conclusion

This was a great opportunity to learn about Python programming and its applications. I was able to understand the importance of input validation, program logic, and code organization. The feedback I received helped me improve my coding skills and create a better application.

## Thank You

Thank you for reviewing my PrepTrack project.
