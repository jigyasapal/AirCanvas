# AIR CANVASE
A basic computer vision application using OpenCV libraries. To create an automated motion recognition system that tracks the movement of the user's hands in front of the camera.

# The main technologies:

Computer Vision- Acquiring processing analysing and understanding images.Theory for building artificial system that obtained information from images.

OPENCV- An open source computer vision and machine learning library written in C++ and Python. Rich set of APIs and tools for computer vision applications like object detection, facial detection, object recognition, speech recognition, and more. Known for its wide range of capabilities and powerful image processing techniques.
MEDIEPIPE- Cross-platform APIs and libraries for deploying solutions. Provides powerful and efficient algorithms for hand detection and tracking. To improve the accuracy and responsiveness of the hand tracking. With MediaPipe, you can create a more accurate and responsive model for hand detection and tracking.
SPEECH RECOGNITION- Model to detect and transcribe the spoken words. Process of converting audio signals into text data(form of voice recognition).
NUMPY- NumPy provides efficient algorithms for array manipulation and numeric computing. Storing the image data, Processing numerical data.
DEQUE- A deque is a double-ended queue in which elements can be both inserted and deleted from either the left or the right end of the queue.
The core elements are- color detection ,tracking and SpeechRecgnition.

##Languages Involved in Your Code:
1. Python 🐍
The main programming language you wrote the code in.
Used for logic, camera input, drawing on frames, handling UI, etc.

2. C++ 💻 (Used Internally)
OpenCV is a library originally written in C++, though you're using its Python bindings.Functions like cv2.line, cv2.imshow, and cv2.VideoCapture() actually call optimized C++ code in the background. That’s why it's super fast even for video processing.

3. C++ & TensorFlow (for MediaPipe) 🧠⚙️
MediaPipe, the hand-tracking library, is built in C++ and uses TensorFlow Lite models.Python only controls and accesses it. It runs machine learning models behind the scenes to detect your hand and fingers.

4. CUDA (optional) ⚡
If your system uses a GPU, OpenCV and MediaPipe can leverage CUDA (based on C/C++) to make everything faster.



