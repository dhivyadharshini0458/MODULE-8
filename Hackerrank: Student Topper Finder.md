# # 🔢 Hackerrank:# 🏆 Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

## 🎯 Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## 💻 PROGRAM:
```
def wrap(string, max_width):
    wrapped_lines = []  # list to store each line
    for i in range(0, len(string), max_width):
        part = string[i:i+max_width]
        wrapped_lines.append(part)
    return '\n'.join(wrapped_lines)  
string, max_width = input(), int(input())
print(wrap(string, max_width))
```

## OUTPUT
<img width="551" height="200" alt="Screenshot 2026-03-28 075531" src="https://github.com/user-attachments/assets/12721026-3072-4910-ab96-7fb65012278d" />

## RESULT
Thus, the Python program defines a function that wraps a long string into multiple lines is executed successfully.
