## Deepfake Detection Using CNN
Deepfake detection model using a custom CNN.

Dataset used: https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images
https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces

## About
This project develops an efficient deepfake detection system using a custom CNN model, trained on the Deepfake and Real Images dataset. With advanced preprocessing and optimization techniques, our model achieves a high Accuracy of 96%, ensuring accurate detection of AI-generated images.

## Features
Custom CNN Model – Designed for accurate deepfake detection with optimized layers.
High Accuracy (AUC Score: 0.97) – Ensures reliable classification of real and fake images.
Advanced Preprocessing – Includes resizing, normalization, and augmentation for better generalization.
Efficient Training – Uses Adam optimizer with batch normalization and dropout to prevent overfitting.
Future Adaptability – Can be extended to detect deepfake videos and evolving manipulation techniques.

## Requirements
Operating System: Windows 10/11, Ubuntu 24.04+ (WSL).
Development Environment: Jupyter Notebook with Python v3.10.
Deep Learning Frameworks: TensorFlow v2.18, CUDA v12.4, cuDNN v9.7.1 for model training.
Image Processing Libraries: Tensorflow / Keras.
Version Control: Implementation of Git for collaborative development and effective code management.
IDE: Use of VSCode as the Integrated Development Environment for coding, debugging, and version control integration.
Additional Dependencies: Includes NumPy, Matplotlib (for data visualization), and Pandas for dataset handling and analysis.

## System Architecture

![image](https://github.com/user-attachments/assets/4652f20b-cd88-4160-8b6c-4ecbb6e49359)



## Output 1 - confusion matrix

![image](https://github.com/user-attachments/assets/1635e794-231e-4710-83a5-7696e14f3466)



#### Output2 - classification report


![image](https://github.com/user-attachments/assets/439c5576-e297-4a4d-ba7e-63b4c828aca5)



#### Output2 - GUI

![image](https://github.com/user-attachments/assets/468dcf7a-f94c-4f99-b129-118b2a5649ac)




## Results and Impact
High Accuracy & Robust Performance – The deepfake detection model achieves an accuracy of 89.1% with a ROC-AUC score of 0.97, demonstrating its effectiveness in distinguishing real and fake images.

Reliable Evaluation Metrics – Performance is validated using precision, recall, F1-score, and confusion matrix, ensuring a well-balanced model with minimal false positives and false negatives.

Scalability & Efficiency – The system processes large-scale deepfake datasets efficiently, making it suitable for real-time detection in cybersecurity, social media moderation, and forensic applications.

Future Improvements – Enhancements such as video deepfake detection, real-time monitoring, and reduced computational overhead will further strengthen its adaptability against evolving deepfake generation techniques.

## Articles published / References
[1] M. S. Rana, B. Murali and A. H. Sung, "Deepfake Detection Using Machine Learning Algorithms", 2021 10th International Congress on Advanced Applied Informatics (IIAI-AAI), Niigata, Japan, 2021, pp. 458-463, doi: 10.1109/IIAI-AAI53430.2021.00079.

[2] Vrizlynn L.L. Thing, “Deepfake Detection with Deep Learning: Convolutional Neural Networks versus Transformers”, 2023 IEEE International Conference on Cyber Security and Resilience (CSR), Venice, Italy, 2023, doi: 10.1109/CSR57506.2023.10225004.

[3] D. Pan, L. Sun, R. Wang, X. Zhang and R. O. Sinnott, "Deepfake Detection through Deep Learning”, 2020 IEEE/ACM International Conference on Big Data Computing, Applications and Technologies (BDCAT), Leicester, UK, 2020, pp. 134-143, doi: 10.1109/BDCAT50828.2020.00001.

[4] A. Malik, M. Kuribayashi, S. M. Abdullahi and A. N. Khan, "DeepFake Detection for Human Face Images and Videos: A Survey", in IEEE Access, vol. 10, pp. 18757-18775, 2022, doi: 10.1109/ACCESS.2022.3151186.

[5] A. Mary and A. Edison, "Deep fake Detection using deep learning techniques: A Literature Review", 2023 International Conference on Control, Communication and Computing (ICCC), Thiruvananthapuram, India, 2023, pp. 1-6, doi: 10.1109/ICCC57789.2023.10164881.

[6] S. R. B. R, P. Kumar Pareek, B. S and G. G, "Deepfake Video Detection System Using Deep Neural Networks", 2023 IEEE International Conference on Integrated Circuits and Communication Systems (ICICACS), Raichur, India, 2023, pp. 1-6, doi: 10.1109/ICICACS57338.2023.10099618.

[7] A. A. Maksutov, V. O. Morozov, A. A. Lavrenov and A. S. Smirnov, "Methods of Deepfake Detection Based on Machine Learning", 2020 IEEE Conference of Russian Young Researchers in Electrical and Electronic Engineering (EIConRus), St. Petersburg and Moscow, Russia, 2020, pp. 408-411, doi: 10.1109/EIConRus49466.2020.9039057.

[8] J. K. Lewis et al., "Deepfake Video Detection Based on Spatial, Spectral, and Temporal Inconsistencies Using Multimodal Deep Learning", 2020 IEEE Applied Imagery Pattern Recognition Workshop (AIPR), Washington DC, DC, USA, 2020, pp. 1-9, doi: 10.1109/AIPR50011.2020.9425167.



