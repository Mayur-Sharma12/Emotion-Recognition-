# Emotion-Recognition-
## Emotion and Face Detection Framework

### Problem Statement:
Existing systems suffer from low accuracy in emotion detection using neural networks and lack secure face databases for real-world applications like human-computer interaction. Training and testing each face demand extensive data, posing challenges in terms of accuracy, data storage, and time.

### Proposed Solution:
Our framework utilizes Gabor filters for efficient feature extraction, enhancing the speed and accuracy of training the deep convolutional neural network (CNN). This approach addresses the limitations in existing systems and proves beneficial in applications such as Graphical Designing, Visual FX, Snapchat/Instagram Filters, Facial Psychology, etc.

### Key Components:
1. **Image Capturing:**
   - The proposed system employs a high-definition web camera to capture images of individuals.
   - OpenCV face detection is applied to identify faces in the captured image frames.

2. **Gabor Filter:**
   - Primarily used in texture analysis, feature extraction, and edge detection.
   - Yields the highest response at edges and points with texture changes when applied to an image.

3. **Convolutional Neural Network (CNN):**
   - Customized architecture using functions like MaxPooling, Flatten, Softmax, ReLU Functions.
   - Classifies images into 7 emotions: Neutral, Happy, Sad, Surprised, Fear, Disgust, and Anger.

**Outcome:**
The experimental results showcase the effectiveness of our proposed features in improving both the speed and accuracy of neural network training. This framework offers a robust solution for real-world applications requiring precise emotion and face detection.
