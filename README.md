#  Virtual Mouse Detection Using Hand Gestures

This project allows users to **control the mouse cursor using hand gestures** captured via a webcam — no physical mouse needed!  
It uses **MediaPipe** for hand tracking, **OpenCV** for video processing, and **PyAutoGUI** for controlling the system mouse.

---

##  Features

- Move the mouse cursor with your **index finger**  
- Perform **left click**, **right click**, and **double click** gestures  
- Take a **screenshot** using a specific hand gesture  
- Real-time detection using webcam feed  

---

##  Technologies Used

- **Python**
- **OpenCV** – for capturing and processing video frames  
- **MediaPipe** – for detecting and tracking hand landmarks  
- **PyAutoGUI** – for controlling the system mouse and screenshots  
- **Pynput** – for simulating mouse button events  
- **NumPy** – for mathematical operations  

---


---

## ⚙️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Deepakdj007/Computer-Vision.git
cd Computer-Vision
2️⃣ Install dependencies
bash
Copy code
pip install opencv-python mediapipe pyautogui pynput numpy
3️⃣ Run the program
bash
Copy code
python live_mouse_control_using_hand_gestures.py
4️⃣ Control Gestures
Gesture	Action
Index finger up	Move cursor
Index bent	Left click
Middle bent	Right click
Both bent	Double click
Thumb close to fingers	Screenshot

Press 'q' to quit the program.

📸 Output Example
Real-time webcam feed with hand landmarks and action labels (e.g., Left Click, Screenshot Taken).

