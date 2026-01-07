# Virtual Keyboard Using Hand Gestures (Python)

This project implements a **virtual on-screen keyboard** that can be controlled using **hand gestures** through a webcam.  
It is built using **Python, OpenCV, and MediaPipe** and allows users to type without using a physical keyboard.

---

## Features
- On-screen virtual keyboard
- Index finger to select keys
- Thumb + index finger pinch to press a key
- Backspace key to delete characters
- Enter key for new lines
- Shift key for single uppercase character
- Caps Lock key for continuous uppercase typing
- Space key support
- Auto-scaling keyboard layout (fits all screen sizes)
- Stable typing with delay control

---

## Gesture Controls

| Gesture | Action |
|-------|--------|
| Index finger hover | Select key |
| Thumb + index pinch | Press key |
| Press SHIFT | Uppercase next character |
| Press CAPS | Toggle Caps Lock |
| Press BACK | Delete last character |
| Press ENTER | New line |
| Press SPACE | Add space |
| Q key | Quit program |

---

## Technologies Used
- Python 3.10 / 3.11
- OpenCV
- MediaPipe

---

## Installation

Make sure Python 3.10 or 3.11 is installed.

Install required libraries:
```bash
py -3.11 -m pip install opencv-python mediapipe
```

---

## How to Run
1. Open Command Prompt
2. Navigate to the project folder:
   ```bash
   cd path/to/virtual-keyboard
   ```
3. Run the program:
   ```bash
   py -3.11 virtual_keyboard.py
   ```
4. Press Q to exit.

---

## Learning Outcomes
- Hand landmark detection
- Gesture-based interaction design
- UI layout and hit-box detection
- Real-time input handling
- State management (Shift and Caps Lock)

---

## Future Improvements
- Key press sound feedback
- Emoji keyboard
- Save typed text to a file
- Improved keyboard UI design

---

## Author
Jatin

If you like this project, consider starring the repository.

