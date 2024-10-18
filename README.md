Keylogger: 
This is a simple keylogger program written in Python that records and logs keystrokes to a text file. It captures each key pressed by the user and saves the information for analysis.

Disclaimer
This program is intended for educational purposes only. Ensure that you have permission to run this keylogger on any system. Unauthorized use of keyloggers can violate privacy laws and ethical guidelines.

Features
Logs every key pressed, including special keys.
Saves keystrokes to a file named keylog.txt.
Stops logging when the Escape key (Esc) is pressed.

Requirements
Python 3.x
pynput library

Installation
You need to install the required library before running the program. Use the following command:

pip install pynput

Usage
Save the Script: Copy the keylogger code into a Python file, for example, keylogger.py.

Run the Program: Execute the script using Python.


python keylogger.py
Start Logging: The program will start logging keystrokes. Press keys as needed.

Stop Logging: Press the Escape key (Esc) to stop the keylogger.

View Logs: Open the keylog.txt file in the same directory to see the recorded keystrokes.

Code Overview

Key Functions
on_press(key): This function is called when a key is pressed. It logs the key to the keylog.txt file.

on_release(key): This function is called when a key is released. It checks if the Escape key is pressed to stop the listener.

Keyboard Listener: The script utilizes pynput.keyboard.Listener to monitor keyboard events.

Important Notes
Ethical Use: Ensure that you only run this program on devices where you have explicit permission to monitor keystrokes.
Testing: It is recommended to test this script in a controlled environment, such as your own personal computer.
Legal Considerations: Be aware of and comply with the laws regarding privacy and monitoring in your jurisdiction.

License
This project is open-source and available for educational use only. Please ensure responsible use of the code provided.

