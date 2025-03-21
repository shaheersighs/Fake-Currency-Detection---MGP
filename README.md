The Fake Currency Detection System is an AI-powered solution that uses deep learning and computer vision to detect counterfeit banknotes in real-time. The project leverages TensorFlow, OpenCV, and Raspberry Pi to analyze key security features like watermarks, holograms, and microtext and classify currency as real or fake. The system consists of several components:  

1) Data Collection & Preprocessing: Capturing real and fake currency images, enhancing features using OpenCV, and applying data augmentation.
2) Model Training: A Convolutional Neural Network (CNN) is trained on a custom dataset and optimized for low-power devices.
3) Model Optimization for Raspberry Pi: The trained model is converted to TensorFlow Lite for fast inference.
4) Real-Time Detection: The Raspberry Pi camera captures currency images, runs the AI model, and provides an instant classification result with a confidence score.
5) User Interface & Feedback: The system outputs a simple "Real" or "Fake" result, with an optional LED or buzzer alert for counterfeit detection.

The repository includes the Python code for image processing, model training, optimization, and deployment on Raspberry Pi.
