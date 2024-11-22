# CSA1289
# Running the Python Script in WSL Ubuntu Terminal

This guide explains how to execute a Python script for generating output files using the `dineroIV` file in a WSL Ubuntu terminal.

## Prerequisites
- Install Python3 on your WSL environment.
- Ensure that the `dineroIV` file exists in a known directory.

## Steps to Run the Python Script

1. **Open WSL Ubuntu Terminal**
   Launch the WSL Ubuntu terminal on your system.

2. **Navigate to the Directory**
   Change the directory to the path where the `dineroIV` file exists. Use the `cd` command for this:
   ```bash
   cd /path/to/dineroIV

Create a Python Script In the terminal, use the nano editor to create a Python file:
nano run_simulations.py
Write the Python Script
Enter your Python script in the editor.
After writing the script, press Ctrl+X to save and exit.
Save the File
When prompted, confirm saving the file by typing Y (Yes).
Press Enter to return to the terminal.
Run the Python Script Execute the created Python script using the following command:
bash
Copy code
python3 run_simulations.py
This will run the script and generate the required output files



