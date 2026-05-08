# 📊 Student Marks Analyzer

A mini data analysis project built using **NumPy** to analyze student marks across multiple subjects.

---

## 🔍 What This Project Does

- Stores student marks in a 2D NumPy matrix (Students × Subjects)
- Calculates **average marks per student** (row-wise)
- Calculates **subject-wise average** (column-wise)
- Finds the **topper** using argmax
- Identifies **failed students** using boolean filtering
- Assigns **grades** (A, B, C, Fail) based on average

---

## 🛠️ Tech Stack

- Python 3
- NumPy

---

## 📁 Project Structure

```
student_marks_analyzer/
│
├── student_marks_analyzer.ipynb   # Main notebook
└── README.md                      # Project info
```

---

## ▶️ How to Run

```bash
# Install NumPy if not installed
pip install numpy

# Open Jupyter Notebook
jupyter notebook student_marks_analyzer.ipynb
```

---

## 📌 Concepts Used

| Concept | Usage |
|--------|-------|
| np.array() | 2D marks matrix banana |
| np.mean(axis=1) | Per student average |
| np.mean(axis=0) | Per subject average |
| np.argmax() | Topper find karna |
| np.any() | Failed students detect karna |
| Boolean Indexing | Condition-based filtering |
| f-strings | Clean output formatting |

---

## 📊 Sample Output

```
Student Grades:
Student 0 --> Average: 84.33 --> Grade: B
Student 1 --> Average: 53.67 --> Grade: C
Student 2 --> Average: 91.67 --> Grade: A
Student 3 --> Average: 37.67 --> Grade: Fail
Student 4 --> Average: 69.67 --> Grade: C
```

---

## 👨‍💻 Author

**Vaibhav Bhoyate**  
BE AIDS Student | Aspiring AI Engineer  
📍 Maharashtra, India

---

## 🚀 Next Steps

- Add student names instead of indexes
- Export results to CSV using Pandas
- Visualize grades using Matplotlib
