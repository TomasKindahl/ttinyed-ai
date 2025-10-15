# Installation Instructions for ttinyed

## What is ttinyed?

ttinyed is a simple graphical text editor written in Python using Tkinter. It allows you to create, open, edit, and save text files, with basic editing features and integration with your system's terminal and file manager.

## Requirements

- Python 3.x
- Tkinter (Python GUI library)

All other modules used (`platform`, `os`, `sys`, `subprocess`) are part of the Python standard library.

## Installing Python

If you do not have Python 3 installed, download and install it from [python.org](https://www.python.org/downloads/).

## Installing Tkinter

Tkinter is included with most Python installations. If you get an error about missing `tkinter`, install it as follows:

### Ubuntu/Debian

```sh
sudo apt-get update
sudo apt-get install python3-tk
```

### Fedora

```sh
sudo dnf install python3-tkinter
```

### Arch Linux

```sh
sudo pacman -S tk
```

### Windows and macOS

Tkinter is included by default. If you encounter issues, reinstall Python from [python.org](https://www.python.org/downloads/).

## Running ttinyed

Clone the repository and run the editor:

```sh
git clone https://github.com/TomasKindahl/ttinyed.git
cd ttinyed
python3 ttinyed.py
```

## Notes

- On Linux, the "Shell" and "File manager" features require `xfce4-terminal` and `thunar` to be installed.
- Keyboard shortcuts are available for most actions (see the source code for details).
- No additional Python packages are required.