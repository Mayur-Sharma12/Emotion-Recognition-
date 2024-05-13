# Emotion-Recognition-

### Problem Statement:
A standalone convolutional neural network (CNN) suffers from low accuracy in emotion detection and lacks real-world applications like human-computer interaction. Training and testing each face demand extensive data, posing challenges in terms of accuracy, data storage, and time.

### Proposed Solution:
Our framework utilizes Gabor filters for efficient feature extraction, enhancing the speed and accuracy a standalone CNN. This approach addresses the limitations in existing systems and proves beneficial in applications such as Graphical Designing, Visual FX, Snapchat/Instagram Filters, Facial Psychology, etc.

<img width="403" alt="Screenshot 2023-12-16 at 8 38 21 PM" src="https://github.com/Mayur-Sharma12/Emotion-Recognition-/assets/93172390/4f3b69dd-09b2-43a2-b76b-f5f4d7f38cd7">


### Key Components:
1. **Image Capturing:**
   - The proposed system employs a high-definition web camera to capture images of individuals.
   - OpenCV face detection is applied to identify faces in the captured image frames.

2. **Gabor Filter:**
   - Primarily used in texture analysis, feature extraction, and edge detection.
   - Yields the highest response at edges and points with texture changes when applied to an image.

<img width="568" alt="Screenshot 2023-12-16 at 8 38 59 PM" src="https://github.com/Mayur-Sharma12/Emotion-Recognition-/assets/93172390/27811846-4645-4bcf-b045-16fff8b4f3a6">

3. **Convolutional Neural Network (CNN):**
   - Customized architecture using functions like MaxPooling, Flatten, Softmax, ReLU Functions.
   - Classifies images into 7 emotions: Neutral, Happy, Sad, Surprised, Fear, Disgust, and Anger.

<img width="520" alt="Screenshot 2023-12-16 at 8 37 43 PM" src="https://github.com/Mayur-Sharma12/Emotion-Recognition-/assets/93172390/2f30ca0b-9e81-4e2c-af1a-2bb747c47c1c">

**Outcome:**
The experimental results showcase the effectiveness of our proposed features in improving both the speed and accuracy of neural network training. This framework offers a robust solution for real-world applications requiring precise emotion and face detection.

<img width="543" alt="Screenshot 2023-12-16 at 8 39 30 PM" src="https://github.com/Mayur-Sharma12/Emotion-Recognition-/assets/93172390/0246b75f-9072-4158-ba34-77301a0dc420">

