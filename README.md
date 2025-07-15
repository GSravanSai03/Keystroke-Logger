Simple Keylogger

The Simple Keylogger is a Python program designed to capture and log keystrokes entered by users. It operates silently in the background, recording keystrokes into a text file.

Features: Keystroke Logging: The program captures and logs keystrokes entered by users. Silent Operation: It operates discreetly in the background without any visible indication to the user. Customization: Users can customize the log file name and location according to their preferences. Termination: The keylogger can be stopped at any time by pressing a predefined key combination. Components: pynput: The library used to monitor keyboard events. Key: Represents keys on the keyboard. Listener: Listens for and handles keyboard events. on_press(key): Function to handle key press events and log keystrokes. on_release(key): Function to handle key release events and stop the keylogger. main(): The main function orchestrating the keylogger's operation and user interaction. How to Use: Run the program. The keylogger starts capturing keystrokes silently in the background. Press the predefined key combination (e.g., 'Esc') to stop the keylogger. Access the keylog.txt file in the same directory as main.py to view the recorded keystrokes. 

Example: Suppose you run the keylogger program and type:

Hello, world! The keylog.txt file will contain:

2025-07-15 13:36:49,648: 'h'
2025-07-15 13:36:49,677: 'e'
2025-07-15 13:36:49,841: 'l'
2025-07-15 13:36:50,037: 'l'
2025-07-15 13:36:50,446: 'o'
2025-07-15 13:36:54,406: 'h'
2025-07-15 13:36:54,578: 'o'
2025-07-15 13:36:54,709: 'w'
2025-07-15 13:36:54,960: Key.space
2025-07-15 13:36:55,309: 'a'
2025-07-15 13:36:55,454: 'r'
2025-07-15 13:36:55,650: 'e'
2025-07-15 13:36:55,706: Key.space
2025-07-15 13:36:56,091: 'y'
2025-07-15 13:36:56,221: 'o'
2025-07-15 13:36:56,402: 'u'
2025-07-15 13:36:56,692: Key.space
2025-07-15 13:37:00,747: Key.backspace
2025-07-15 13:37:01,020: Key.shift
2025-07-15 13:37:01,160: '?'
2025-07-15 13:37:01,572: Key.space
2025-07-15 13:37:01,738: Key.shift
2025-07-15 13:37:01,817: 'I'
2025-07-15 13:37:01,919: Key.space
2025-07-15 13:37:02,063: 'a'
2025-07-15 13:37:02,186: 'm'
2025-07-15 13:37:02,263: Key.space
2025-07-15 13:37:02,677: 'g'
2025-07-15 13:37:02,926: 'o'
2025-07-15 13:37:03,068: 'o'
2025-07-15 13:37:03,471: 'd'
2025-07-15 13:37:03,622: Key.space
2025-07-15 13:37:03,903: 'h'
2025-07-15 13:37:04,018: 'e'
2025-07-15 13:37:04,285: 'r'
2025-07-15 13:37:04,511: 'e'
2025-07-15 13:37:05,050: Key.shift
2025-07-15 13:37:05,286: '!'
2025-07-15 13:37:10,396: Key.esc

Requirements: Python 3.x pynput library Usage: python main.py 

Note: Ensure that you have Python installed on your system before running the program.

Disclaimer This keylogger program is provided for educational purposes only. Do not use it for illegal activities. Respect the privacy and consent of others before using this software.
