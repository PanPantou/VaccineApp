# 💉 VaccineApp

*A Java console application for managing patient vaccination records.*

![Java](https://img.shields.io/badge/Java-8%2B-orange?logo=openjdk\&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Console-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

### 📖 Overview

**VaccineApp** is a lightweight Java console program designed to manage patient vaccination data.
It allows users to record patient information, recommend vaccines based on allergies, and generate analytical reports — showcasing clean Java logic and structured console interaction.

This project demonstrates practical use of **arrays**, **collections**, **regex validation**, and **sorting** in Java.

---

### 🧩 Features

✅ Add new patient records interactively
✅ Recommend vaccine type automatically based on allergy
✅ Validate all user inputs (ID, name, age, date, etc.)
✅ Display multiple reports:

* Count of patients by vaccine type
* Count of patients by allergy type
* Patients sorted by **vaccine type** or **age**
  ✅ Identify:
* Patients who completed **3 doses**
* **Elderly patients (70+)** with fewer than three doses
  ✅ Structured modular design for readability and maintainability

---

### ⚙️ Technologies

| Component     | Details                       |
| ------------- | ----------------------------- |
| **Language**  | Java                          |
| **Version**   | Java 8 or higher              |
| **Libraries** | Standard Java (`java.util.*`) |
| **Type**      | Console Application           |

---

### 🚀 How to Run

#### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/VaccineApp.git
cd VaccineApp
```

#### 2️⃣ Compile the program

```bash
javac VaccineApp.java
```

#### 3️⃣ Run the program

```bash
java VaccineApp
```

#### 4️⃣ Follow the console menu

```
Menu:
1. New Entry
2. Generate Report
Enter your choice (1 or 2):
```

---

### 🧠 Example Interaction

```
Enter ID (must be a positive integer): 101
Enter Name (cannot be empty): John
Enter Last Name (cannot be empty): Smith
Enter Age (must be a positive integer): 75
Enter Allergy (choose from: PEG, PS80, Gelatin): PEG
Recommended Vaccine: AstraZeneca
Enter Vaccine Type (AstraZeneca): AstraZeneca
Enter Date (MM-DD-YYYY format): 11-10-2025
```

---

### 📊 Example Output

```
Number of patients with Pfizer vaccine: 3
Number of patients with AstraZeneca vaccine: 4

Patients with AstraZeneca vaccine, sorted by last name:
ID   First Name   Last Name   Age   Allergy   Vaccine   Date
2    John         Smith       75    PEG       AstraZeneca   11-10-2025

Number of patients by allergy type:
PEG: 2
PS80: 1
Gelatin: 3
```

---

### 🧪 Key Concepts Demonstrated

* **Input validation** using regex and predefined options
* **Dynamic data management** with 2D arrays and collections (`Map`, `Set`, `List`)
* **Sorting and filtering** using Java’s `Comparator` and stream APIs
* **Method decomposition** for clear, reusable code
* **Console interaction** and data visualization via formatted output

---
