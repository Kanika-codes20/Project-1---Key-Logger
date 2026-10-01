# Basic Python Keylogger

A basic Python keylogger created as an educational project to understand how keyboard input can be captured and processed programmatically.

## Educational & Ethical Use

This project is intended only for **learning and authorized security research**.

Keyloggers can capture sensitive information such as passwords, messages, and other private input. Do not use this program to monitor another person's device or collect information without their explicit permission.

## About the Project

This project demonstrates how a Python program can listen for keyboard events using the `pynput` library.

When a key is pressed, the program processes the key and writes the resulting character to a local `log.txt` file.

The program also handles several special keyboard keys, including:

- Space
- Shift
- Left Ctrl
- Right Ctrl
- Enter
- Backspace

The keyboard listener continues running and processes key presses as they occur.

## Technologies Used

- Python
- `pynput`

## Python Concepts Practiced

- Importing modules
- Functions
- Function parameters
- String conversion
- String manipulation
- Conditional statements
- File handling
- Appending data to a text file
- Using a library's event listener

## What I Learned

This project helped me understand how Python can interact with keyboard events and how external libraries can provide functionality beyond Python's built-in features.

It also helped me understand why unauthorized keylogging is a serious cybersecurity and privacy concern.

## Project Structure

```text
Basic-Python-Keylogger/
│
├── keylogger.py
├── README.md
└── .gitignore
```

The `log.txt` file is intentionally not included in the repository because it is generated during program execution and may contain sensitive keyboard input.

## Limitations

This is a very basic educational implementation.

It does not attempt to provide advanced keylogging features, stealth mechanisms, persistence, remote data collection, or other capabilities associated with malicious keyloggers.

## Project Context

This project was created while learning beginner Python and exploring cybersecurity concepts.

It also helped motivate the development of a defensive cybersecurity project, **CyberSentinel**, which focuses on detecting potentially suspicious processes and monitoring file integrity.

---

**Educational project — use responsibly and only with authorization.**
