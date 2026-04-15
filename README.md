# Python-LCA2

**Contributors:**
Diganta Dantale, roll number- 67,
Anish Ghodekar 71,
Swanandi Wadghule 72,
Namya Prasad 74

**CGPA Calculator and Target GPA Predictor**

**Overview**

This project is a desktop-based application developed using Python and Tkinter. It is designed to assist students in calculating their CGPA and determining the required GPA to achieve a desired target.

The application provides a simple and interactive user interface with two main functionalities:

1. CGPA calculation based on grades and credits


2. Prediction of required GPA to reach a target CGPA




**Features**

CGPA Calculator

Accepts multiple subjects with grade and credit inputs

Computes overall CGPA

Displays total accumulated credits

Allows dynamic addition of subject entries


**Target GPA Predictor**

Accepts:

Current CGPA

Completed credits

Target CGPA

Remaining credits

Calculates required GPA

Indicates feasibility of achieving the target



**Technology Stack**

Programming Language: Python

GUI Framework: Tkinter

Libraries Used:

tkinter

ttk

messagebox



**Installation and Execution**

1. Clone the repository:



git clone https://github.com/your-username/cgpa-tool.git

2. Navigate to the project directory:



cd cgpa-tool

3. Run the application:



python main.py


**Working Principle**

CGPA Calculation

CGPA is calculated using the weighted average formula:

CGPA = Σ(Grade × Credits) / Σ(Credits)


**Required GPA Calculation**

Required GPA is computed using:

Required GPA = [(Target CGPA × Total Credits) − (Current CGPA × Completed Credits)] / Remaining Credits


---

**Error Handling**

Validates empty input fields

Ensures numeric input for all entries

Checks for mismatch in grades and credits

Displays appropriate error messages



**User Interface**

Tab-based layout for clear separation of functionalities

Simple and user-friendly design

Dynamic input handling



**Future Enhancements**

Support for grade-to-point conversion

Data persistence functionality

Export of results

Enhanced UI design


**Conclusion**

This application provides a practical and efficient solution for students to manage and predict their academic performance. It is lightweight, easy to use, and built entirely using standard Python libraries.

