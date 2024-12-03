# Batch Script for Consolidating Java Files

This repository contains a batch script to automate the process of consolidating multiple Java files into a single output text file. The script processes files named in the format `task##.java` (where `##` is a number between 01 and 99) and merges their content into a well-organized text file.

---

## Features
- Automatically processes all `task##.java` files in the directory.
- Creates an output file named `Assignment_<AssignmentNumber>_<UserID>_<UserName>.txt`.
- Validates the format of input files to ensure only correctly named files are included.
- Provides helpful prompts for user inputs.

---

## How to Use
1. **Prepare Your Files**:
   - Ensure all Java files follow the naming convention `task##.java` (e.g., `task01.java`, `task23.java`).
   - Place this script in the same directory as the Java files.

2. **Run the Script**:
   - Open a Command Prompt (Windows).
   - Navigate to the directory containing this script and the Java files.
   - Execute the script by typing:
     ```cmd
     CSE110submissionFormatScript.bat
     ```

3. **Provide User Input**:
   - Follow the prompts to enter:
     - Assignment Number (e.g., 01)
     - User ID
     - Your Name

4. **Check Output**:
   - The consolidated file will be generated with a name like:
     ```
     Assignment_<AssignmentNumber>_<UserID>_<UserName>.txt
     ```

---

## Example
Given the following Java files in the directory:
- `task01.java`
- `task02.java`
- `task03.java`

When you run the script and provide the following inputs:
- **Assignment Number**: `03`
- **User ID**: `24301222`
- **User Name**: `Gabe Newell`

The output will be:
Assignment 03_24301222_Gabe Newell.txt
