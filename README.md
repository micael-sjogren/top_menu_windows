# Minimalistic Menu

A simple and minimalist menu application that allows you to execute scripts, launch programs, and explore endless possibilities! Use this menu to organize and manage your scripts and applications effortlessly.

## Features

- Execute batch files, PowerShell scripts, Python scripts, shortcuts, executable files, and more.
- Highly customizable menu settings for positioning, colors, and display.

## Prerequisites

- **Python**: If you plan to execute Python scripts, ensure Python is installed on your computer.

## Setup Instructions

1. **Copy Files**:
   - Copy `Main.exe` and `Main.exe.config` to a desired folder on your computer (e.g., `C:\menu\Main\8500_Source`).

2. **Configure the Menu**:
   - Open `Main.exe.config` and set the path to your menu items (e.g., `C:\menu\Main\`).

3. **Add Menu Scripts**:
   - Place your script files in the configured directory (e.g., `C:\menu\Main\`).

4. **Using Python Scripts**:
   - Ensure Python is installed on your system to execute Python scripts from the menu.

### File Naming Convention

To ensure proper sorting in the menu:

- **Prefix**: Add a four-digit number followed by an underscore at the beginning of all files and folders (e.g., `1000_example_script.bat`).
- **Sorting**: If the four-digit prefix is higher than `8000`, that item will not appear in the menu.
- **Dividers**: To create a divider in the submenu, create an empty text file named `1000_x---------------x.txt`.

## Customization

Feel free to explore and modify the `Main.exe.config` settings to adjust:

- **Positioning**: Change the layout of the menu items.
- **Colors**: Customize the visual appearance of the menu.

---

This version organizes the information into sections for easier readability, uses consistent formatting, and enhances clarity. Let me know if you need further adjustments or additional content!

![image](https://github.com/user-attachments/assets/ec50421b-a827-42a8-9978-847e2882281b)

![image](https://github.com/user-attachments/assets/462e1333-e548-44dc-8a58-92e7eefcc6a4)
