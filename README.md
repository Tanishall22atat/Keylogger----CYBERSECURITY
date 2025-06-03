#🧐 What Is a Keylogger?

A keylogger (short for keystroke logger) is a software program or hardware device that records every key pressed on a keyboard. Its primary function is to capture and log input data from the user in real-time, often storing it in a file for later review.


# 🔐 Keystroke Logger using Python (`pynput`)

A lightweight keystroke logger built using Python's `pynput` library to capture and store keyboard inputs in real-time.

## 📌 Overview

This project demonstrates how to monitor and log keyboard events for learning purposes. It uses the `keyboard.Listener` module from the `pynput` package to track each keystroke and writes them to a file named `keyfile.txt`.

> ⚠️ **Disclaimer:**
> This project is strictly for educational and ethical use only. Do **not** use this tool to capture input without a user's informed consent. Unauthorized use is illegal and unethical.

## 💻 How It Works

* Listens to every key pressed by the user
* Attempts to extract the character of the key
* Appends the keystroke to a local file `keyfile.txt`
* Handles exceptions where a character key is not detected (e.g., `Shift`, `Enter`, `Ctrl`)

## 🛠️ Prerequisites

* Python 3.x
* `pynput` library

Install the required library:

```bash
pip install pynput
```

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/keystroke-logger.git
   cd keystroke-logger
   ```

2. **Run the script**

   ```bash
   python keylogger.py
   ```

3. **Check the output**

   * Logged keys will be stored in `keyfile.txt`.

## 📂 File Structure

```
keylogger.py       # Main script to capture keystrokes
keyfile.txt        # Output file where keys are saved
README.md          # Project documentation
```

## 🔒 Ethical Use

This project was created for learning purposes only. If you're using this to understand how keyloggers work from a cybersecurity perspective or to build safe user-input monitoring tools (with full consent), that's the intent.

**Do not use maliciously.**


