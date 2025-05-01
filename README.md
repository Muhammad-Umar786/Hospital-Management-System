
# Hospital Management System

A console-based **Hospital Management System** developed in C++ using Object-Oriented Programming (OOP) principles. The system allows for patient management, staff registration, doctor appointment scheduling, password protection, and hospital details viewing. It utilizes file handling to store and retrieve records for persistent data storage.

---

## 👨‍💻 Developed By

- **Name**: Muhammad Umar
- **Course**: BS Computer Science – 3rd Semester
- **Subject**: Object-Oriented Programming (OOP)
- **Project Type**: Semester Project

---

## 💡 Features

- **Password-Protected Login**
- **Patient Record Management**
- **Staff Information Handling**
- **Doctor Information & Appointment Booking**
- **Detailed Hospital Information Display**
- **Persistent File Handling for Data Storage**
- **Modular Class-Based Design with Inheritance & Polymorphism**

---

## 🛠️ Tools & Technologies

- **Language**: C++
- **IDE**: Code::Blocks / Dev C++ / Visual Studio
- **File Handling**: `.txt` and `.bin` for storing data
- **Platform**: Windows (uses `conio.h`, `windows.h`)

---

## 🏗️ Project Structure

### ➤ Main Classes:

| Class Name | Role |
|------------|------|
| `one` | Abstract base class with virtual methods `get()` and `show()` |
| `info` | Inherits from `one`, handles patient information |
| `Ali`, `Ahmed`, `Sara`, `Alishba` | Specialized classes for different doctors (inherit from `info`) |
| `staff` | Handles hospital staff data (inherits from `one`) |
| `information` | Displays detailed information of doctors |
| `menu()` | Central navigation menu for the system |
| `passcode()` / `cpasscode()` | Password validation and creation |

---

## 📁 Files Used

- `patient.txt`: Stores general patient records
- `Ali.txt`, `Ahmed.txt`, `Sara.txt`, `Alishba.txt`: Individual doctor appointment records
- `staff.txt`: Contains staff records
- `drinfo.txt`: Doctor profile and availability
- `password.txt`: Stores user password for login authentication

---

## 🧪 Functional Flow

### 🔐 Login Screen
- Password protected.
- User must enter matching password and confirmation.
- Option to change password available in the main menu.

### 🏥 Main Menu Options
1. **Hospital Information** – Overview of hospital features
2. **Doctor Information** – View doctor specialties, timings, and fee
3. **Doctor Appointment** – Book appointment with one of four doctors
4. **Save Staff Info** – Enter and store staff details
5. **View Patient Info** – Display saved patient records
6. **View Staff Info** – Display saved staff records
7. **Change Password** – Update login password
8. **Exit** – Terminate program

---

## 🧬 Object-Oriented Concepts Used

- **Inheritance**: Classes like `Ali`, `Ahmed`, etc. inherit from `info`.
- **Polymorphism**: Base class `one` is used for pointer-based polymorphic function calls.
- **Abstraction**: `one` serves as an abstract class enforcing contract of `get()` and `show()`.
- **Encapsulation**: Data members are kept private or protected.

---

## 📌 Sample Run (Overview)

```
Welcome to JOAYO HOSPITAL ISB

1. Hospital Information
2. Doctor Information
3. Book Appointment
4. Save Staff Info
5. View Patient Info
6. View Staff Info
7. Change Password
8. Exit

Enter Your Choice: _
```

---

## ✅ How to Compile and Run

### Compile:
```bash
g++ hospital.cpp -o hospital.exe
```

### Run:
```bash
hospital.exe
```

*Note: Run on Windows as it uses Windows-specific headers like `conio.h` and `windows.h`.*

---

## 📂 Output Files Created

| File Name     | Purpose                    |
|---------------|----------------------------|
| `Ali.txt`     | Ali (Skin specialist) appointments |
| `Ahmed.txt`   | Ahmed (Child specialist) appointments |
| `Sara.txt`    | Sara (Heart specialist) appointments |
| `Alishba.txt` | Alishba (DVM) appointments |
| `patient.txt` | General patient info       |
| `staff.txt`   | Staff records              |
| `drinfo.txt`  | Doctor profile information |
| `password.txt`| User password storage      |

---

## 📝 Future Enhancements (Optional)

- GUI version using Qt or C++/CLI
- Database integration (MySQL, SQLite)
- Role-based access (Admin vs Receptionist)
- Advanced search and update/delete features

---

## 📢 Disclaimer

This project is for educational purposes. All data is saved locally and not encrypted. For real hospital systems, security and database integration must be added.

---

## 📧 Contact

For any queries, feel free to contact:

**Muhammad Umar**  
Email: *[Your Email Here]*  
Institute: PMAS Arid Agriculture University, UIIT  
