# Human-Activity-Classification-Using-RF-Signals-and-Machine-Learning
This project focuses on detecting and classifying human activities—such as walking, sleeping, and falling—using radio frequency (RF) signals and machine learning techniques. The RF signals, collected by a specialized radar device, are used as input features for training a machine learning model capable of identifying distinct human activities.

A Random Forest Classifier was trained on simulated RF signal data, which was preprocessed to extract meaningful features in both the time and frequency domains. The signals were filtered, and relevant features such as Fast Fourier Transform (FFT) were used to capture frequency-based patterns in the signal, which correlate with different human activities.

The model was evaluated using metrics such as accuracy, precision, recall, and the confusion matrix, demonstrating its effectiveness in distinguishing between various human activities. The project has applications in healthcare, security, and monitoring systems, where non-invasive detection of human activity through RF signals is critical.
