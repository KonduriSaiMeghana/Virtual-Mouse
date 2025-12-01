# Virtual Hand-Gesture Mouse Controller

Control your computer mouse using just your hand and a webcam  

This project uses **MediaPipe Hands** for hand landmark detection and maps simple gestures to mouse actions like moving the cursor, left/right click, double-click, and taking screenshots.

---

## Features

- Real-time hand tracking using your webcam
- Cursor movement using index finger
- Gesture-based mouse actions:
  - **Move mouse** – point with your index finger
  - **Left click**
  - **Right click**
  - **Double click**
  - **Screenshot capture** (saved with random filenames)
- Visual feedback: overlay of hand landmarks and gesture text on the video frame

---

## Tech Stack

- **Python**
- **OpenCV** – webcam capture & display
- **MediaPipe** – hand landmark detection
- **PyAutoGUI** – control mouse & take screenshots
- **pynput** – click events
- **NumPy** – geometric computations
- Jupyter Notebook (`virtual.ipynb`)

---

## Requirements

- **OS**: Windows / macOS / Linux  
- **Python**: 3.8 or higher  
- **Hardware**:
  - A working **webcam** (built-in or external)
  - Mouse & keyboard (for emergency override – e.g., pressing `q` to quit)

---

