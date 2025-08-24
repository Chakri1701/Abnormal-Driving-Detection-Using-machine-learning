A desktop Tkinter application that detects and labels driving behaviors from video in near real time using a compact Keras and TensorFlow convolutional neural network. The app reads frames with OpenCV, preprocesses them, runs inference, and overlays the predicted label on the video stream.

 Features

- Point and click GUI built with Tkinter to load or generate the model, choose a video, and start or stop monitoring
- Frame by frame inference with OpenCV: capture, preprocess to 150x150, predict, overlay, display
- Modular layout that separates source code, data, and model files
- Large files such as datasets and model weights are kept out of version control by default
