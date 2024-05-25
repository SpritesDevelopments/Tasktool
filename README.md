# Task Tool

This is a simple task management tool built using Python's Tkinter library. It allows you to add, remove, and manage tasks in a graphical user interface (GUI).

## About This Setup Tool

The setup tool included in this project is generated using the Inno Setup Script Wizard. It facilitates the installation process by creating a setup wizard for deploying the application on Windows systems.

## Features

- Add tasks
- Remove tasks
- Minimize to system tray
- Run on startup (platform-dependent)

## Requirements

- Python 3.x
- Tkinter
- customtkinter
- pystray
- PIL (Python Imaging Library)
- win32com.client (Windows only)

## Installation

1. Clone or download the repository.
2. Run the setup file `Setup_Task_Tool_1.0.exe` to install the application on your Windows system.
3. Run the script `Tasktool.exe` to launch the application.

## Usage

- **Adding a Task:** Enter the task in the input field and click on the "Add Task" button.
- **Removing a Task:** Click on the "Remove" button next to the task you want to remove.
- **Minimize to Tray:** Click on the "Minimize to Tray" button to hide the application in the system tray.
- **Run on Startup:** Click on the "Run on Startup" button to enable the application to run automatically when the system starts (platform-dependent).



## Team

- Spritedev - Project Lead
- Spritedev - Developer
- Sprite's Network - Team 

## Platform Compatibility

- **Windows:** The application supports running on startup by creating a shortcut in the startup folder.
- **macOS:** Maybe coming.
- **Linux:** Maybe coming.

## License

This project is licensed under the [MIT License](LICENSE).
