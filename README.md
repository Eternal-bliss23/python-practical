# Python Practical — Semester 3

Solutions to the 25 questions from **Practice Programs.pdf** for the Semester 3
Python practical course. The programs cover core Python, file handling,
exception handling, NumPy and Pandas.

## Contents

| # | Program |
|---|---------|
| 1 | Student Result Processing System |
| 2 | Employee Salary Calculation System |
| 3 | String Analysis System |
| 4 | Electricity Bill Calculator |
| 5 | Number Analysis Using Loops |
| 6 | Shopping Cart Using Lists |
| 7 | Student Marks Management Using Lists |
| 8 | Tuple-Based Employee Record Management |
| 9 | Set Operations for Student Activities |
| 10 | Library Management Using Dictionaries |
| 11 | Banking System Using User-Defined Functions |
| 12 | Function-Based Number Operations |
| 13 | Lambda, Map, Filter and Reduce |
| 14 | File-Based Student Record Management |
| 15 | File Analysis and Word Frequency |
| 16 | Exception Handling in Banking Transactions |
| 17 | Exception Handling in Student Data Processing |
| 18 | Matrix Addition and Subtraction Using NumPy |
| 19 | Matrix Multiplication and Determinant Using NumPy |
| 20 | Vector Operations Using NumPy |
| 21 | Statistical Analysis Using NumPy |
| 22 | Student Dataset Preprocessing Using Pandas |
| 23 | Employee Dataset Analysis Using Pandas |
| 24 | Sales Data Analysis Using Pandas |
| 25 | Integrated Python Data Processing System |

## Requirements

- Python 3.x
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- Jupyter Notebook or [VS Code](https://code.visualstudio.com/) with the Python
  extension (to run the notebook interactively)

Install the libraries with:

```bash
pip install numpy pandas notebook
```

## How to run

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/python-practical.git
   cd python-practical
   ```

2. Open `Practice_Programs_Solutions.ipynb` in Jupyter Notebook or VS Code:

   ```bash
   jupyter notebook
   ```

3. Run the cells from top to bottom. Most programs ask for input in the cell
   output area.

`app.py` is a small NumPy test script:

```bash
python app.py
```

## Files created when the programs run

Several programs write output files into this folder:

| File | Program |
|------|---------|
| `students.txt` | Q14 |
| `paragraph.txt`, `paragraph_copy.txt` | Q15 |
| `students_cleaned.csv` | Q22 |
| `employees.csv` | Q23 |
| `sales.csv` | Q24 |
| `student_report.csv` | Q25 |

These generated files are ignored by Git.

## Project structure

```text
.
├── Practice_Programs_Solutions.ipynb   # All 25 solutions with explanations
├── app.py                              # Small NumPy array example
├── first.ipynb                         # Empty practice notebook
├── practice.ipynb                      # Empty practice notebook
├── .gitignore                          # Ignores .venv, checkpoints, caches
└── README.md                           # This file
```
