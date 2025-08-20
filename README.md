# 📘 CGPA Calculator

A simple **C++ program** that calculates the **Cumulative Grade Point Average (CGPA)** based on user input of courses, grades, and credit hours.

---

## 🚀 Features
- Allows user to enter multiple courses.
- Accepts **letter grades (A+, A, B+, B, C+, C, D, F)**.
- Converts letter grades to grade points.
- Computes **CGPA** using weighted average (grade points × credit hours).
- Displays course-wise details in a clean tabular format.

---

## 🛠️ Compilation & Execution
### **Compile the program**
```bash
g++ cgpa_calculator.cpp -o cgpa_calculator
```

### **Run the program**
```bash
./cgpa_calculator
```

---

## 📥 Input Format
1. Enter the number of courses.
2. For each course:
   - Enter course name
   - Enter grade (A+, A, B+, B, C+, C, D, F)
   - Enter credit hours

---

## 📤 Output Example
```
📘 CGPA Calculator
Enter number of courses: 3

Course 1 name: Math
Grade: A
Credits: 4

Course 2 name: Physics
Grade: B+
Credits: 3

Course 3 name: Chemistry
Grade: C
Credits: 2

---------------------------------------
Course       Grade     Credits
Math         A         4
Physics      B+        3
Chemistry    C         2
---------------------------------------
Your CGPA is: 7.67
```

---

## 📊 Grading Scale
| Grade | Points |
|-------|--------|
| A+    | 10.0   |
| A     | 9.0    |
| B+    | 8.0    |
| B     | 7.0    |
| C+    | 6.0    |
| C     | 5.0    |
| D     | 4.0    |
| F     | 0.0    |

---

## 📌 Notes
- If an **invalid grade** is entered, it will return `-1.0` internally.
- You can modify the grade mapping inside `gradeToPoint()` function as per your grading system.

---

## 👨‍💻 Author
Developed by *Piyush Raj* ✨
