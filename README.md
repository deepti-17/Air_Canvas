Air Canvas Using Python 🎨
Overview
Air Canvas is an interactive drawing application that allows users to draw in real-time using hand gestures captured by a webcam. This project leverages computer vision techniques to provide a touch-free drawing experience with multiple color options, enabling users to unleash their creativity without traditional input devices.

Features
Real-Time Drawing: Draw on a virtual canvas using hand movements.
Multiple Colors: Switch between different colors for enhanced creativity.
Gesture-Based Control: Start, stop, and change colors using simple gestures.
Interactive Feedback: See the pointer on the screen to guide your drawing.
Technologies Used
Python: Core programming language.
OpenCV: For real-time image processing and gesture recognition.
NumPy: To handle array-based operations and improve efficiency.
How It Works
The webcam captures the video feed in real time.
Color detection is used to identify the pointer (e.g., a colored cap or marker) based on predefined HSV color ranges.
The pointer's movement is tracked and mapped onto a virtual canvas.
Users can select different colors to draw by interacting with virtual color palettes.
