# University-Management-System

# 🎓 College Management System (Python - OOP Based CLI Project)

This is a simple **College Management System** implemented in **Python** using **Object-Oriented Programming (OOP)** concepts. The project runs in the **Command-Line Interface (CLI)** and allows users to manage multiple colleges along with their students and teachers.

## 📌 Features

- ✅ Create multiple colleges dynamically  
- ✅ Add students to specific colleges  
- ✅ Add teachers to specific colleges  
- ✅ Display student and teacher details per college  
- ✅ Prevents duplicate college creation  
- ✅ Menu-driven interface for easy navigation  

## 🧱 Object-Oriented Design

- `Person`: Base class for `Student` and `Teacher`
- `Student`: Inherits from `Person` and adds `branch` attribute
- `Teacher`: Inherits from `Person` and adds `subject` attribute
- `College`: Contains lists of `students` and `teachers` and methods to manage them

## 💻 How It Works

1. **Create College** – Adds a new college unless it already exists.
2. **Add Student** – Inputs student details and assigns them to the selected college.
3. **Add Teacher** – Inputs teacher details and assigns them to the selected college.
4. **Display Students** – Lists all students in a selected college.
5. **Display Teachers** – Lists all teachers in a selected college.
6. **Exit** – Closes the program.

## 🛠️ Technologies Used

- Python 3
- Object-Oriented Programming (Inheritance, Classes)
- CLI-based user input and logic

## 📈 Future Enhancements

- Save and load data from files or database
- Add validation for duplicate roll numbers
- GUI interface using Tkinter or PyQt
- Role-based login for Admin, Students, Teachers

## 📷 Sample Screenshot 
![image](https://github.com/user-attachments/assets/f1c34c8c-ed02-413d-b38a-7d6ea5d60603)

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---

Let me know if you want this formatted as a `README.md` file or want to include additional badges, images, or GitHub topics.
