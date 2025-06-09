# Virtual Mouse Controller

This project implements a virtual mouse controller using computer vision. It leverages **OpenCV**, **MediaPipe**, and **PyAutoGUI** to control the mouse cursor with hand gestures detected via a webcam. The index finger is used to move the cursor, and a click action is triggered when the thumb and index finger come close together.

---

## Features

- Real-time hand tracking using webcam
- Cursor movement controlled by index finger
- Click detection when index finger and thumb are close
- Smooth and responsive UI experience

---

## Technologies Used

- [OpenCV](https://opencv.org/) - for capturing video and image processing
- [MediaPipe](https://developers.google.com/mediapipe) - for real-time hand detection and tracking
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) - for controlling the mouse cursor and performing click actions

---


## How to Use

1. Run the main Python file:

```bash
python main.py
```

2. Make sure your webcam is enabled and your hand is visible on screen.
3. Move your **index finger** to move the mouse cursor.
4. To click, bring your **thumb** and **index finger** close together.

---

## Notes

* Make sure you're in a well-lit environment for better hand detection.
* The project may not work well if multiple hands or objects are detected.
* Screen resolution is considered during scaling, so the cursor movement maps accurately.

---

## Project Structure

```
virtual-mouse-controller/
│
├── main.py               # Main file to run the program
├── README.md             # Project documentation
```
