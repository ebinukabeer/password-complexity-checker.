## 🔐 Password Complexity Checker

This project is a simple Python-based tool that assesses the strength of a password based on various criteria. It helps users create strong passwords by providing feedback on how to improve them.

### ✅ Features

* Evaluates password based on:

  * Minimum length (8 characters)
  * Uppercase letters
  * Lowercase letters
  * Numbers
  * Special characters
* Gives a strength rating:

  * Very Weak
  * Weak
  * Moderate
  * Strong
  * Very Strong
* Provides feedback on missing components

---

### 🛠 How It Works

The script uses regular expressions to check the presence of different character types in the password. Based on how many criteria the password meets, a strength score is calculated and feedback is generated.

---

### 💻 How to Run

1. Clone or download this repository.
2. Ensure you have Python installed.
3. Open a terminal in the project directory.
4. Run the script:


   python passcheck.py
   
5. Enter a password when prompted to see the strength and suggestions.

---

### 📁 File Structure


password-complexity-checker/
│
├── passcheck.py   # Main Python script
└── README.md             # Project documentation


---

### 📝 Example Output

```
Enter a password to check: Hello123

Password Strength: Moderate
Suggestions to improve your password:
- Include at least one special character.


---

### 📌 Requirements

* Python 3.x (no external libraries required)
