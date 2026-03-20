# 🎓 Student Stream Allocation System (C++)

A console-based **Student Stream Allocation System** built in C++ that automates assigning students to academic streams (Science, Commerce, Arts) based on merit and eligibility criteria.

---

## 📌 Overview

This project simulates a real-world school admission workflow:

- Admin defines eligibility criteria and seat capacity
- Students enter their academic details and preferred stream
- System evaluates performance and assigns streams
- Generates eligible lists and merit-based rankings

---

## 🚀 Features

### 👨‍💼 Admin
- Basic authentication system
- Set minimum percentage for each stream
- Define seat availability

### 👨‍🎓 Student
- Add new student records
- Append to existing records
- Input subject-wise marks and preferences

### ⚙️ Stream Allocation
- Automatic percentage calculation
- Stream assignment based on:
  - Student preference
  - Eligibility criteria

### 📊 Data Handling
- File-based storage using `fstream`
- Maintains separate files for each stream

### 🏆 Merit List
- Sorts students by percentage
- Generates ranked lists for each stream

---

Admin sets criteria
↓
Students enter data
↓
System calculates percentage
↓
Stream allocation
↓
Eligible lists created
↓
Merit lists generated

---

## 🗂️ File Structure

| File Name   | Description |
|------------|------------|
| `student`  | Stores student records |
| `criteria` | Stores eligibility rules |
| `elig_sc`  | Science eligible students |
| `eligcom`  | Commerce eligible students |
| `eligart`  | Arts eligible students |
| `sell_sc`  | Science merit list |
| `sellcom`  | Commerce merit list |
| `sellart`  | Arts merit list |

---

## 🛠️ Tech Stack

- **Language:** C++
- **Concepts Used:**
  - Classes & Structures
  - File Handling (`fstream`)
  - Sorting Algorithms
  - Console-based UI

- **Dependencies:**
  - `iostream`
  - `fstream`
  - `conio.h` (legacy)
  - `dos.h` (legacy)

---

## ▶️ How to Run

### Using Turbo C++ / DOSBox (Recommended)
1. Open project in Turbo C++
2. Compile the code
3. Run the executable

### Using Modern Compiler (Optional)
You may need to:
- Remove `conio.h` and `dos.h`
- Replace:
  - `clrscr()` → custom clear function
  - `gets()` → `cin.getline()`

---

## 🔐 Default Credentials
Username: rimi
Password: rimi


---

## 📸 Menu
1. Create/Modify Criteria
2. Enter Student Data
3. Allot Stream
4. Display Criteria
5. Display Allotted Streams
6. Display All Students
7. Merit List
8. Exit

---

## ⚠️ Limitations

- Uses outdated libraries
- Fixed-size data structures
- No database integration
- No seat allocation enforcement logic
- Basic (insecure) authentication

---

## 💡 Future Improvements

- Upgrade to modern C++ (C++17+)
- Replace file system with database (MySQL/SQLite)
- Add proper seat allocation logic
- Build GUI or web-based interface
- Implement secure authentication

---

## 📈 Learning Outcomes

- File handling in C++
- Data structuring using classes
- Sorting and ranking logic
- Real-world system simulation

---

## 🤝 Contribution

Contributions are welcome:
- Refactor code
- Improve performance
- Add features
- Modernize architecture

---

## 📄 License

This project is for educational purposes.
