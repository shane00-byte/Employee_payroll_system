
# 🧾 Employee Payroll System (C++)

This is a simple C++ console program that calculates an employee's **weekly pay**, including **overtime compensation**.

It demonstrates:
- Basic **class design** (`Employee`)
- **Encapsulation** of payroll logic
- **Input validation** and error handling
- Use of **constants** and **formatted output**

---

## 🚀 Features

✅ **Calculates weekly salary based on:**
- Hourly rate  
- Hours worked

✅ **Handles overtime pay:**
- Overtime kicks in **after 40 hours**  
- Overtime pay is **1.5×** the normal rate

✅ **Includes input safety:**
- Prevents crashes on invalid inputs (like letters instead of numbers)

---

## 💻 Example Run



===== Employee Payroll System =====
Calculating salary for: Jane Doe
Hourly Rate: $25.5
Overtime rate (over 40 hrs): 1.5x
---------------------------------

Enter total hours worked this week: 45

--- Payroll Summary ---
Employee: Jane Doe
Hours Worked: 45
Total Salary: $1203.75
======================

```

---

## 🧠 How It Works

1. The program creates an `Employee` object with a name and hourly rate.  
2. It asks the user to enter total hours worked.  
3. The class function `calculateSalary()`:
   - Calculates **regular pay** (up to 40 hours)
   - Adds **overtime pay** (1.5× rate for hours above 40)
4. The total pay is displayed with proper formatting.

---

## 🧩 Code Structure

```

├── EmployeePayroll.cpp   # Main program file
└── README.md             # This file

````

**Key components:**
- `Employee` class — encapsulates employee info and salary logic  
- `calculateSalary()` — computes total weekly pay  
- `clearInputBuffer()` — handles invalid input cleanup  
- `main()` — manages input/output and ties everything together

---

## ⚙️ Compilation & Execution

### 🖥️ Using g++
```bash
g++ -o payroll EmployeePayroll.cpp
./payroll
````

### 🧱 Using an IDE (e.g., Code::Blocks, Visual Studio, VS Code)

* Create a new C++ console project.
* Copy the code into the main file.
* Build and run.

---

---

## 🛠️ Future Improvements

* Ask user for name and rate dynamically
* Handle multiple employees using a vector
* Write payroll summaries to a `.txt` or `.csv` file
* Add unit tests for salary calculation

---

## 📜 License

This project is open-source and free to use for educational or personal purposes.

---
