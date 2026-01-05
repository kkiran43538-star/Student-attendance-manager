# 📘 Student Attendance Manager  
**Python Mini Project**

---

## 👤 Student Details
- **Name:** Kiran S  
- **USN:** 1BG24BA054  
- **Course:** Python Programming  
- **Date:** January 2025  

---

## 📌 Project Overview

The **Student Attendance Manager** is a **menu-driven, console-based Python application** designed to help students efficiently track and manage their class attendance.  
It provides a digital solution to record attendance, calculate attendance percentages, and identify subjects with low attendance.

---

## ❗ Problem Statement

Students often face difficulties in tracking attendance across multiple subjects. Manual methods can lead to:
- Miscalculations  
- Missed attendance warnings  
- Last-minute realization of attendance shortages  

This project automates attendance tracking to ensure accuracy and reliability.

---

## 🎯 Objectives

- Record attendance as **Present** or **Absent**
- Calculate **subject-wise attendance percentage**
- Identify subjects below **75% attendance**
- Store attendance records permanently using files
- Provide a simple **menu-driven interface**

---

## 🧠 System Design & Approach

- Uses a **list of dictionaries** to store attendance data  
- Each record contains:
  - Subject name  
  - Date  
  - Attendance status  
  - Timestamp  
- The program runs continuously until the user chooses to exit  

---

## 🛠 Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- openpyxl
- datetime module

---

## 🧩 Modules & Functions

| Function Name | Description |
|--------------|------------|
| `mark_attendance()` | Record attendance for a subject |
| `show_all_subjects()` | Display attendance summary |
| `view_all_records()` | Show all attendance records |
| `search_by_subject()` | Search records by subject |
| `calculate_percentage()` | Calculate attendance percentage |
| `show_warnings()` | Display subjects below 75% |
| `delete_record()` | Delete an attendance record |
| `load_data()` | Load data from Excel file |
| `save_data()` | Save data to Excel file |

---

## 💾 File Handling

- Attendance data is stored in an Excel file named **`attendance.xlsx`**
- Data is:
  - Loaded when the program starts  
  - Saved when the program exits  
- Ensures **data persistence** across multiple executions

---

## 🖥 Output Demonstration

1. Program start and main menu  
2. Marking attendance  
3. Attendance summary view  
4. Attendance warning output  
5. Viewing all records  
6. Excel file with saved attendance data  

---

## ✅ Results

- Attendance is accurately recorded  
- Percentages are calculated correctly  
- Warnings are displayed for low attendance  
- Data is reliably stored using Excel files  

---

## 🏁 Conclusion

The **Student Attendance Manager** simplifies attendance tracking and helps students stay informed about their attendance status.  
It demonstrates Python fundamentals, data structures, functions, file handling, and exception handling.

---

## 🚀 Future Enhancements

- Add a **Graphical User Interface (GUI)**
- Generate attendance **reports and charts**
- Support **multiple student profiles**
- Add **notification alerts** for low attendance  

---

## ▶ How to Run

1. Open the project in **Jupyter Notebook**
2. Run all cells
3. Follow the on-screen menu instructions
