#  Random Password Generator

This is a **Python-based Random Password Generator** that creates secure passwords using alphabets (upper and lower case), numbers, and special characters based on a user-defined length. It follows a **50-30-20 ratio** for character distribution.

---

##  Features

- Minimum password length of **8 characters**
- Uses:
  - **50% Alphabets**
  - **30% Numbers**
  - **20% Special Characters**
- Converts some alphabets to **uppercase randomly**
- Shuffles characters for randomness
- Easy-to-understand code with comments

---

##  Technologies Used

- Python 3
- `random` module
- `math` module

---

##  Formula Used

For a given password length:

- **Alphabets:** `50%` → `length // 2`
- **Numbers:** `30%` → `ceil(length * 0.3)`
- **Special Characters:** Remaining after alphabets and numbers

---

##  Sample Output

```bash
Enter Password Length: 12
Generated Password: g8T@t5hD9&e!
```

---

##  How to Run

1. Make sure Python is installed on your system.
2. Save the file as `password_generator.py`.
3. Open terminal or command prompt.
4. Run the script:

```bash
python password_generator.py
```

---

##  File Structure

```
random-password-generator/
│
├── password_generator.py
└── README.md
```

---

##  Purpose of This Project

- Practice **Python fundamentals**
- Learn to work with **strings, lists, loops, and randomness**

---

##  License

This project is open-source and free to use.

---
