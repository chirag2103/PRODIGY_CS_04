# Simple Python Keylogger

The Simple Python Keylogger is a basic keylogging script that captures keystrokes and logs them into a text file (`keylog.txt`). It uses the `pynput` library to monitor keyboard events.

## Features

- **Keystroke Logging**: Records all keystrokes including letters, numbers, and special characters.
- **User-friendly**: Starts logging keystrokes upon execution and stops when the 'Esc' key is pressed.
- **Minimalist**: Uses a straightforward implementation to demonstrate keylogging functionality.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/chirag2103/Keylogger.git
    ```
   
2. **Navigate to the project directory**:
    ```sh
    cd Keylogger
    ```
   
3. **Install dependencies**:
    The keylogger uses the `pynput` library, which can be installed using pip:
    ```sh
    pip install pynput
    ```

## Usage

1. **Run the keylogger**:
    ```sh
    python Keylogger.py
    ```
   
2. **Logging Keystrokes**:
    - The keylogger starts logging keystrokes immediately after execution.
    - Press the 'Esc' key to stop the keylogger and terminate logging.

3. **View Logs**:
    - All logged keystrokes are saved in the `keylog.txt` file in the same directory.

## Example

```plaintext
Keylogger is running... Press 'Esc' to stop.
