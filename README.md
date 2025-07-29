# 📋 Clipboard Text Formatter

A simple Python app that cleans and reformats copied text from your clipboard. Perfect for writers, students, content creators, or anyone tired of messy text from emails, PDFs, or websites.

## 🚀 Features

- ✅ Remove unnecessary line breaks  
- ✅ Add bullet points to each line  
- ✅ Strip extra whitespace  
- ✅ Automatically copy the cleaned result back to the clipboard  
- 🖥️ GUI (`tkinter`) for one-click formatting

## 🧪 Before and After

**Input:**  

**Output:**  


## 🧰 Built With

- [`pyperclip`](https://pypi.org/project/pyperclip/) – clipboard control  
- [`re`](https://docs.python.org/3/library/re.html) – regex cleanup  
- `tkinter` – *(optional)* simple GUI interface

## 📦 Installation

### Step 1: Clone or Download the Repository

```bash
git clone https://github.com/yourusername/clipboard-text-formatter.git
cd clipboard-text-formatter
```

### Step 2: Install Required Package

Only pyperclip is required:
```bash
pip install pyperclip
```

📝 tkinter usually comes pre-installed with Python.

## ▶️ How to Run the Script
### Option 1: Run the Command-Line Version
```bash
python format_clipboard.py
```

### Option 2: Use the GUI Version
```bash
python format_clipboard_gui.py
```
