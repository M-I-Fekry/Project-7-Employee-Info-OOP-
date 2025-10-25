# 🧑‍💻 Employee Management Class – C++

## 📘 Overview
This project defines a simple **Employee Management System** using **Object-Oriented Programming (OOP)** concepts in **C++**.  
It demonstrates how to encapsulate employee-related data and operations within a class, providing methods for managing and interacting with employee information.

---

## 📚 Training Source

This project was developed as part of the training Roadmap with
Dr. Mohamed AbouHadhood 👨‍🏫

🔗 [AbouHadhood Platform](https://programmingadvices.com/)

---

## 🧩 Class Details
### **Class Name:** `clsEmployee`

### **Attributes:**
- `int _ID` — Employee ID  
- `string _FirstName` — Employee’s first name  
- `string _LastName` — Employee’s last name  
- `string _Title` — Employee’s job title  
- `string _Email` — Employee’s email address  
- `string _Phone` — Employee’s phone number  
- `double _Salary` — Employee’s salary  
- `string _Department` — Department name  

### **Main Methods:**
| Method | Description |
|--------|--------------|
| `Print()` | Displays employee information in a formatted way. |
| `SendEmail(string Subject, string Body)` | Simulates sending an email to the employee. |
| `SendSMS(string TextMessage)` | Simulates sending an SMS message to the employee. |
| `GetFullName()` | Returns the full name (first + last name). |
| Setter & Getter Methods | Allow controlled access to private attributes. |

---

## 🧠 Concepts Used
- **Encapsulation**
- **Class & Object Creation**
- **Constructor Overloading**
- **Access Modifiers (Private/Public)**
- **Getter & Setter Functions**
- **Console Input/Output**

---

## 🧾 Example Output

```
Info :
********************************
ID         : 100030
First Name : Mohamed
Last Name  : Ibrahim
Full Name  : Mohamed Ibrahim
Title      : Software Developer
Email      : MyEmail@gmail.com
Phone      : +20.........
Salary     : 5000
Department : Computer Science
********************************

The following message sent successfully to email : MyEmail@gmail.com
Subject : ^_^ Hi ^_^
Body : How are you?

The following SMS message sent successfully to phone : +20.........
How are you?
```

---

## 🚀 How to Run
1. Copy the code into a file named `Employee.cpp`.
2. Compile it using any C++ compiler, e.g.:
   ```bash
   g++ Employee.cpp -o EmployeeApp
   ```
3. Run the executable:
   ```bash
   ./EmployeeApp
   ```
4. The program will display the employee info and simulate sending messages.

---

## 🏗️ Future Enhancements
- Add file handling to save and load employee data.  
- Implement inheritance (e.g., `clsManager`, `clsDeveloper` classes).  
- Add input validation and interactive user menu.

---

## 📄 License
This project is open-source and free to use for learning and educational purposes.

---

**Author:** Mohamed Ibrahim  
**Language:** C++  
**Project Name:** Employee-Inheritance-System-OOP  
