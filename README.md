# Tomato and Potato Disease Detection Using YOLOv8

![Tomato and Potato Disease Detection](https://via.placeholder.com/600x400)

In this project, I trained a YOLOv8 model to detect diseases in tomato and potato plants. Accurate and timely detection of plant diseases is essential for effective crop management, and YOLOv8 offers the ability to perform real-time detection, making it a suitable choice for agricultural applications.

## Evaluation Metrics
- **mAP (Mean Average Precision):** 33.2%
- **Precision:** 45.2%
- **Recall:** 33.0%

These metrics reflect the model's current performance in detecting tomato and potato diseases. With a precision of 45.2%, the model correctly identified 45.2% of the predicted disease instances, while the recall of 33.0% indicates that the model detected 33.0% of all actual diseased instances.

## Model Architecture
The YOLOv8 model was chosen for its capability to detect multiple disease symptoms across various stages of plant growth. Despite the challenges posed by similar visual symptoms in different diseases, YOLOv8's architecture allowed for real-time detection.

## Training Process
The model was trained on a dataset of tomato and potato plant images, including images of healthy plants and those affected by various diseases. Data augmentation techniques such as rotation, scaling, and color jittering were used to help the model generalize better. The training process aimed to strike a balance between underfitting and overfitting, with a focus on improving recall.

## Results
While the current results show that the model has room for improvement, achieving a mAP of 33.2% indicates that it can detect certain diseases under specific conditions. Further improvements could be achieved by expanding the dataset and refining the augmentation strategies.


