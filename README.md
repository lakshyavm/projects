#STUDENT REPORT CARD GENERATOR (GRADE SYSTEM )



This is a simple console-based Student Report Card Generator written in Python. It collects student names and their marks for Math, English, and Science, calculates averages and grades, identifies top performers, and computes subject-wise statistics. The program is packaged as an executable (.exe) file for easy use on Windows systems.

## Features

- **Enter Multiple Students:** Prompt for student names and their marks.
- **Auto Calculate Grades:** Grades are assigned based on average marks.
- **Generate Individual Reports:** View each student’s score breakdown and grade.
- **Identify Subject Toppers:** Find the highest scorer in each subject.
- **Class Statistic Reports:** Compute class average and identify students scoring above 90 in any subject.
- **Rank Students:** See students ranked by total marks.
- **Windows Standalone Application:** Distributed as an easy-to-run executable file; no Python installation required.

## How to Use

### 1. **Run the Program**
- Double-click the `.exe` file (`marks.exe`) if you're on Windows.
- Alternatively, run the Python script using  
  ```bash
  python marks.py
  ```

### 2. **Input Data**
- Enter the number of students.
- For each student, input their name and marks in Math, English, and Science as prompted.

### 3. **View Reports**
- The program will display:
    - Each student's marks, average, and grade.
    - Subject toppers.
    - Students who scored above 90 in any subject.
    - Subject-wise class averages.
    - Student ranking list.

### 4. **Pause Before Exit**
- When the report is complete, the program will show:
  ```
  Program finished. Press Enter to close this window.
  ```
  Press Enter to close or review the output before exiting.

## Example Usage

```
Enter number of students: 2
Enter student name: Alice
Math score: 95
English score: 88
Science score: 90
Enter student name: Bob
Math score: 80
English score: 85
Science score: 82
```

_Reports and statistics will be displayed as described above._

## How to Build the EXE Yourself (Optional)

1. Install PyInstaller with:
   ```
   pip install pyinstaller
   ```
2. Generate the executable:
   ```
   python -m pyinstaller --onefile marks.py
   ```
3. Your `.exe` file will be found in the `dist` directory.

## Notes

- Enter numeric values only for marks.
- The console program will not close until you press Enter, so you have time to review the output.

**Enjoy using the Student Grade System!**
