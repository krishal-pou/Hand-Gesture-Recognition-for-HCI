
# 🤖 **Hand Gesture Recognition for Human-Computer Interaction** ✋

Welcome to the **Hand Gesture Recognition for Human-Computer Interaction (HCI)** project! This project aims to provide a way for users to interact with computers using hand gestures, creating an intuitive and natural user interface. ✨

## 🚀 **Features**:
- **Real-Time Hand Gesture Recognition**: Uses a webcam to recognize hand gestures and trigger actions.
- **Human-Computer Interaction**: Allows users to control the computer through simple hand gestures.
- **Machine Learning**: Uses Keras to train a model that classifies hand gestures based on a set of predefined gestures.
- **Interactive Visualizations**: Uses Plotly for real-time visual feedback of gestures.
- **Keyboard and Mouse Control**: Uses Pynput to simulate keyboard and mouse events based on recognized gestures. 🖱️⌨️

## 🌐 **Technologies Used**:
- **Keras** - For deep learning model to recognize gestures.
- **OpenCV** - For hand detection and capturing the live webcam feed.
- **Plotly** - For visualizing the recognition process and gesture feedback.
- **Pynput** - For controlling the computer’s keyboard and mouse using gestures.
- **Python** - The main programming language used in the project.

## 💡 **How It Works**:
1. **Hand Gesture Detection**: OpenCV captures frames from the webcam and detects the user's hand using image processing techniques.
2. **Gesture Classification**: A pre-trained Keras model is used to classify different hand gestures.
3. **Interaction**: Once a gesture is recognized, corresponding actions are triggered (like clicking the mouse, typing keys, or other interactions).
4. **Real-Time Feedback**: Plotly visualizations provide feedback to the user on what gesture is being recognized.

## 📸 **Demo**:
- The system uses a webcam to capture hand gestures and display the corresponding actions on the screen.
- Users can perform gestures like clicking, scrolling, or pressing keys without touching the keyboard or mouse.

## 🛠️ **Installation Instructions**:
1. Clone this repository:
    ```bash
    git clone https://github.com/krishal-pou/Hand-Gesture-Recognition-for-HCI.git
    ```
2. Navigate to the project folder:
    ```bash
    cd hand-gesture-recognition-hci
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the main Python script:
    ```bash
    python main.py
    ```

## ⚙️ **Requirements**:
- Python 3.x
- **OpenCV**: For webcam feed and hand detection.
- **Keras**: For gesture recognition model.
- **Plotly**: For real-time visualization.
- **Pynput**: For keyboard and mouse control.

Install dependencies using:
```bash
pip install opencv-python keras tensorflow plotly pynput
```

## 🎨 **Design & User Interface**:
- The user interacts with the system using simple hand gestures in front of the webcam.
- Each gesture corresponds to a predefined action, such as scrolling, clicking, or typing a letter.
- Visual feedback is provided through **Plotly** to show the progress and status of gesture recognition.


## 📣 **Contributions**:
Feel free to fork this repository and submit pull requests if you have any improvements or new features you'd like to add.

