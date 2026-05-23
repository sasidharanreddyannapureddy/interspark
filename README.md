# File Automation Tool

## Overview
The File Automation Tool is a Python-based automation project developed to perform file management operations such as renaming files, sorting files by extension, and cleaning temporary files automatically.

This project uses the Python OS module, exception handling, logging functionality, and user input support to automate repetitive file operations efficiently.

---

# Features

- Rename files automatically
- Sort files into folders based on file extensions
- Delete temporary files
- Generate operation logs
- Handle errors using exception handling
- Accept user input dynamically

---

# Technologies Used

- Python
- OS Module
- shutil Module
- Exception Handling
- File Handling

---

# Project Structure

```text
file_automation_project/
│
├── main.py
├── logs.txt
├── README.md
└── test_files/
```

---

# Functionalities

## 1. Rename Files
The program automatically renames files in sequential order.

Example:
```text
photo.jpg → file_1.jpg
notes.txt → file_2.txt
```

---

## 2. Sort Files
The program sorts files into folders according to their extensions.

Example:
```text
image.jpg → JPG folder
notes.txt → TXT folder
music.mp3 → MP3 folder
```

---

## 3. Clean Temporary Files
The program deletes unwanted temporary files such as:

```text
.tmp
.temp
.bak
```

---

# Exception Handling

The project uses exception handling to avoid program crashes during:
- Invalid folder paths
- Permission issues
- Missing files
- File operation errors

Example:
```python
try:
    files = os.listdir(folder)
except Exception as e:
    print(e)
```

---

# Logging System

All operations are stored in a log file named:

```text
logs.txt
```

Example log:
```text
2026-05-23 10:15:30 - Renamed photo.jpg to file_1.jpg
2026-05-23 10:16:10 - Deleted cache.tmp
```

---

# How to Run the Project

## Step 1
Install Python.

Download Python:
https://www.python.org/downloads/

---

## Step 2
Clone the repository.

```bash
git clone https://github.com/your-username/file-automation-project.git
```

---

## Step 3
Open terminal or command prompt.

Navigate to project folder:

```bash
cd file-automation-project
```

---

## Step 4
Run the Python file.

```bash
python main.py
```

---

# Sample Input

```text
Enter folder path:
C:\Users\Admin\Downloads\TestFiles

1. Rename Files
2. Sort Files
3. Clean Temp Files

Enter your choice:
2
```

---

# Sample Output

```text
Moved: image1.jpg → JPG
Moved: notes.txt → TXT
Moved: music.mp3 → MP3
```

---

# Sample Log Output

```text
2026-05-23 10:15:30 - Moved image1.jpg to JPG
2026-05-23 10:15:31 - Moved notes.txt to TXT
2026-05-23 10:15:32 - Moved music.mp3 to MP3
```

---

# Advantages

- Saves time
- Reduces manual work
- Organizes files automatically
- Improves productivity
- Beginner-friendly Python project

---

# Future Enhancements

- GUI interface using Tkinter
- Automatic scheduled cleanup
- File compression support
- Duplicate file detection
- Cloud storage integration

---

# Author

Name: Your Name  
Project: File Automation Tool  
Technology: Python Automation Project

---

# GitHub Repository

Add your GitHub repository link here:

```text
https://github.com/your-username/file-automation-project
```

---

# License

This project is developed for educational and learning purposes.
