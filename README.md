# PythonProjects
# Python Projects: BMI Calculator & Automated File Sorter

## Project 1: BMI Calculator

### Overview

The BMI (Body Mass Index) Calculator is a simple Python script that allows users to input their weight and height to calculate their BMI. Based on the calculated BMI, the program categorizes the user's weight status into categories such as underweight, normal weight, overweight, or obese.

### How It Works

- **Input**: The user provides their weight (in pounds) and height (in inches).
- **Calculation**: The script calculates BMI using the following formula:
  
### How to Run the Project

1. **Set Up the Environment**:
   - Ensure you have Python installed along with Jupyter Notebook.
   - Launch Jupyter Notebook using the terminal or command prompt:

2. **Open the Notebook**:
   - Navigate to the directory where your notebook (`BMI_Calculator.ipynb`) is located and open it.

3. **Run the Notebook**:
   - Execute the cells in the notebook one by one.
   - You will be prompted to enter your weight and height.
   - The notebook will calculate your BMI and display the result along with your weight category.



## Project 2: Automated File Sorter

### Overview

The Automated File Sorter is a Python script implemented in a Jupyter Notebook. It is designed to organize files in a specified directory by sorting them into folders based on their file types. This project helps in managing files by automatically categorizing them into appropriate folders, making your directory neat and easy to navigate.

### Supported File Types

The script sorts files into the following categories:

- **Text Files**: `.txt`
- **CSV Files**: `.csv`
- **Image Files**: `.jpg`, `.jpeg`

### How It Works

- **Scanning**: The script scans the specified directory for files.
- **Sorting**: It identifies the file types based on extensions and moves them into corresponding folders:
  - Text files are moved to a "Text Files" folder.
  - CSV files are moved to a "CSV Files" folder.
  - Image files are moved to an "Image Files" folder.

If these folders do not exist, the script will create them automatically.

### How to Run the Project

1. **Set Up the Environment**:
   - Make sure you have Python installed along with Jupyter Notebook.
   - Install any necessary dependencies, such as `os` and `shutil`, which are typically included in the standard Python library.

2. **Open the Jupyter Notebook**:
   - Launch Jupyter Notebook in your terminal or command prompt:
   
     ```bash
     jupyter notebook
     ```

   - Navigate to the directory where your notebook (`automated_file_sorter.ipynb`) is located and open it.

3. **Run the Notebook**:
   - Follow the instructions provided in the notebook.
   - You will be prompted to enter the path of the directory you wish to sort.
   - Execute the cells in the notebook to sort the files.
