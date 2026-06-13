
# GestureX AI

GestureX AI is an AI-powered touchless virtual mouse system that enables users to control computer functions using real-time hand gestures. The system utilizes Computer Vision and Machine Learning techniques with OpenCV and MediaPipe to detect, track, and recognize hand movements through a webcam.

The project provides a natural and contactless Human-Computer Interaction (HCI) experience by allowing users to perform cursor movement, left click, right click, double click, drag-and-drop, scrolling, volume control, and brightness adjustment using hand gestures without requiring any additional hardware.

GestureX AI is designed to demonstrate the practical application of Artificial Intelligence, Computer Vision, and Gesture Recognition in creating intuitive and accessible user interfaces.

**Recommended Python Version:** 3.12

# Features

_click on dropdown to know more_ <br>

### Gesture Recognition:

<details>
<summary>Neutral Gesture</summary>
 <figure>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/palm.gif" alt="Palm" width="711" height="400"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>

<details>
<summary>Move Cursor</summary>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/e20edfb1f368ffa600d96bd91031942ec97cb2ab/demo_media/move%20mouse.gif" alt="Move Cursor" width="711" height="400"><br>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/left%20click.gif" alt="Left Click" width="711" height="400"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/right%20click.gif" alt="Right Click" width="711" height="400"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/double%20click.gif" alt="Double Click" width="711" height="400"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Scrolling</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Scrolling.gif" alt="Scrolling" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for horizontal and vertical scroll. The speed of scroll is proportional to the distance moved by pinch gesture from start point. Vertical and Horizontal scrolls are controlled by vertical and horizontal pinch movements respectively.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/drag%20and%20drop.gif" alt="Drag and Drop" width="711" height="400"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

<details>
<summary>Multiple Item Selection</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/multiple%20item%20selection.gif" alt="Multiple Item Selection" width="711" height="400"><br>
 <figcaption>Gesture to select multiple items</figcaption>
</details>







## Getting Started
### Procedure


### Step 1: Clone the Repository


git clone https://github.com/Archita-26/GestureX-AI.git
cd GestureX-AI


### Step 2: Verify Python Installation

Ensure that Python 3.12 or later is installed on your system.

Check version:

```bash
python --version
```

Expected Output:

```bash
Python 3.12.x
```

### Step 3: Install Required Libraries

Install all required dependencies:

```bash
pip install -r requirements.txt
```

If requirements.txt is unavailable, install dependencies manually:

```bash
pip install opencv-python mediapipe pyautogui numpy comtypes pycaw screen-brightness-control
```

### Step 4: Navigate to Source Directory

```bash
cd src
```

### Step 5: Run GestureX AI

```bash
python gesturex_controller.py
```

### Step 6: Start Using Hand Gestures

* Allow webcam access.
* Keep your hand visible in front of the camera.
* Ensure proper lighting conditions.
* Use supported hand gestures to control the mouse cursor.

### Requirements

* Python 3.12
* Webcam
* Windows Operating System
* OpenCV
* MediaPipe
* NumPy
* PyAutoGUI

```

### Note

For best performance, ensure proper lighting conditions and keep your hand clearly visible to the webcam.
```


## Future Enhancements

The following features are planned for future development and optimization:

* Voice Assistant Integration
* Voice-Based Application Control
* Enhanced Gesture Accuracy and Recognition
* Additional Custom Gesture Support
* AI-Powered User Interaction Features
* Improved Cross-Platform Compatibility
* Advanced Accessibility Features
* Gesture-Based File and System Management

These features are currently under development and will be included in future versions of GestureX AI.


## Collaborators

### Archita Temre

* GitHub: https://github.com/Archita-26
* Email: [architatemre2610@gmail.com](mailto:architatemre2610@gmail.com)
* LinkedIn: https://www.linkedin.com/in/archita-temre-92b131340/y

### Abhijeet Sharma

* GitHub: https://github.com/abhijeetsharma77
* Email: [abhijeetsharmash@gmail.com](mailto:abhijeetsharmash@gmail.com)
* LinkedIn: https://www.linkedin.com/in/abhijeet-sharma-05328433a


### Jatin Aserkar

* GitHub: https://github.com/jatinaserkar
* Email: [jatinaserkar10a@gmail.com](mailto:jatinaserkar10a@gmail.com)
* LinkedIn: https://www.linkedin.com/in/jatin-aserkar-77688328b


### Himanshu Jain

* GitHub: https://github.com/jn-himanshu07
* Email: [Himanshujan0703@gmail.com](mailto:Himanshujan0703@gmail.com)
* LinkedIn: https://www.linkedin.com/in/himanshu-jain-547666327