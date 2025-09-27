# 📌 Smart Task Management System

A **console-based C++ project** that helps users **manage daily tasks** efficiently with features like adding, updating, deleting, and marking tasks as completed. The system also ensures **time conflict validation** for pending tasks and provides a neat **task summary view** with color coding.

Prepared by.. Group 3 of OOP students:
1. Tayyab Hanif (2024-SE-11)
2. Mahdi Ali (2024-SE-16)
3. Qazi Zarnab (2024-SE-14)

---

## ✨ Features

* ➕ **Add Task** – Create new tasks with title, description, priority, and time.
* 📋 **View Tasks** – Display all tasks in detail or view a summarized table.
* ⏳ **Pending Task Management** – Shows pending tasks separately.
* ✅ **Mark Tasks Completed** – Select multiple task IDs at once to mark them as done.
* ✏️ **Update Task** – Edit task details with duplicate-time checks.
* ❌ **Delete Tasks** – Remove one or more tasks by IDs.
* 💾 **File Handling** – Tasks are saved to a file (`tasks.txt`) and reloaded on the next run.
* 🎨 **Colored Console Output** – Easy differentiation between priorities and statuses.

---

## 🛠️ Technologies Used

* **Language:** C++
* **IDE:** Dev C++ (or any C++ compile)
* **Libraries Used:**

  * `<iostream>`
  * `<iomanip>`
  * `<fstream>`
  * `<stdexcept>`
  * `<string>`
  * `<windows.h>`

---

## 📂 Project Structure

```
Smart-Task-Management/
│
├── main.cpp            # Contains main function and utility functions
├── task.h              # Task class
├── time.h              # Time class
├── filehandler.h       # File handling class
├── taskmanager.h       # TaskManager class
├── menu.h              # Menu (UI handling) class
└── tasks.txt           # Saved tasks data (auto-generated)
```

---

## 📊 Class Design

* **Time** – Represents task time (hours, minutes).
* **Task** – Holds details of each task.
* **FileHandler** – Manages saving/loading tasks from file.
* **TaskManager** – Core logic to add, delete, update, complete tasks.
* **Menu** – Handles user interface and interaction.

---

👤 Tayyab Hanif
🎓 2nd Semester C++ Project

---
