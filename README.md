# DragonLaserSight

A customizable on-screen laser dot overlay application with real-time controls and configuration persistence.

## Features

- Customizable dot color, size, opacity, and brightness
- Persistent configuration settings
- Hotkey support for quick actions
- User-friendly control panel
- Always-on-top display
- Administrator privileges for proper keyboard hook handling

## Requirements

- Windows OS
- Python 3.7+
- Administrative privileges (required for global hotkey functionality)
- Required Python packages (see requirements.txt)

## Installation

1. Clone this repository or download the source code
2. Install required packages:
```bash
pip install -r requirements.txtUsage

    Run the script with administrative privileges:

bash

python laser_dot.py

    Control Panel Features:
        Opacity slider (0.1 - 1.0)
        Brightness slider (0.1 - 1.0)
        Size slider (5 - 50 pixels)
        Color picker button
        Visibility toggle button

    Hotkeys:
        F9: Toggle dot visibility
        F10: Open color picker
        ESC: Save settings and quit

Configuration

The application automatically saves your settings to laser_dot_config.json. This includes:

    Dot size
    Dot color
    Opacity
    Brightness
    Visibility state

Technical Details

    Uses Tkinter for the GUI
    Implements transparent window overlay
    Global hotkey support via keyboard module
    Color manipulation using colorsys
    JSON-based configuration persistence

Troubleshooting

    Permission Error:
        Ensure you're running the script with administrative privileges
        Right-click and select "Run as Administrator"

    Hotkeys Not Working:
        Verify the keyboard module is properly installed
        Check for conflicts with other applications
        Ensure administrative privileges

    Display Issues:
        Verify your system supports transparent windows
        Check for conflicts with other overlay applications

Known Limitations

    Requires administrative privileges
    Windows-specific functionality
    May conflict with other applications using global hotkeys

Author
Jayson Rivers privesec010110@gmail.com

Acknowledgments

    Thanks to the keyboard module developers
    Tkinter community for documentation and support

