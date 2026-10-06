# 🗂️ File Sorter in Python

This project is a simple Python script that automatically organizes files in a directory into folders based on their extensions.  
It helps keep your workspace clean by grouping files like `.txt`, `.py`, `.jpg`, etc., into separate folders.

---

## 📜 How It Works
1. The script lists all files in the current directory.
2. It checks each file:
   - Skips directories.
   - Skips files without an extension.
3. Creates a folder for each unique extension (if not already present).
4. Moves the file into its corresponding folder.

---

## 🚀 Usage
1. Place the script in the folder you want to organize.
2. Run the script:
   ```bash
   python file_sorter.py
