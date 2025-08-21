 
### Virtual Mouse

Control your computer hands-free with this Python-based virtual mouse\!

-----

### **Overview**

This project is a virtual mouse that uses computer vision to track hand gestures and control the cursor. It is built entirely in Python, using libraries like OpenCV for video capture and image processing, and `pyautogui` for mouse control.

-----

### **Features**

  * **Hand Gesture Tracking:** Utilizes a webcam to detect and track your hand.
  * **Scrolling:** Scroll up or down by moving a specific hand gesture.
  * **Clicking:** Perform left and right clicks using distinct hand signs.
  * **System Control:** Seamlessly moves the cursor and interacts with the operating system.

-----

### **How It Works**

The program works in three main steps:

1.  **Hand Landmark Detection:** The webcam captures a video feed. The code then detects key points on your hand, like the fingertips and palm, using an AI model.
2.  **Gesture Recognition:** It analyzes the position and distance between these landmarks to identify specific gestures (e.g., an open hand for scrolling, a closed fist for clicking).
3.  **Mouse Control:** Based on the recognized gesture, the program uses the `pyautogui` library to move the mouse cursor, click, or scroll accordingly.

-----

### **Getting Started**

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/your-repository-name.git
    ```

2.  **Install Dependencies:**
    You will need to install the required libraries. Navigate to the project directory and run the following command:

    ```bash
    pip install opencv-python mediapipe pyautogui
    ```

3.  **Run the Program:**
    Once the dependencies are installed, you can run the main Python script:

    ```bash
    python main.py
    ```

-----

### **Contributing**

Contributions are welcome\! If you have any ideas or suggestions for improvements, feel free to open an issue or create a pull request.

-----

### **License**

This project is open-sourced under the MIT License.
