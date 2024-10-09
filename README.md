What Happened in This Project?

In this project, we built a face recognition pipeline using the LFW (Labeled Faces in the Wild) dataset. Here is a summary of what we did:

Dataset Loading: We loaded a set of face images from the LFW dataset, which contains labeled images of famous people.

![image](https://github.com/user-attachments/assets/47692afe-b6a0-4ca2-9da7-4f2ff3eed3c7)

Figure 1: Example face images from the LFW dataset.

Feature Extraction with HOG: We extracted HOG (Histogram of Oriented Gradients) features from each image. HOG helps in capturing the structure and shape of faces by analyzing the gradients in the image.

![image](https://github.com/user-attachments/assets/57d9d641-5922-46b4-ab4f-7791737ce0cf)

Figure 2: Extracted HOG features from the face images.

Model Training with SVM: We trained an SVM (Support Vector Machine) classifier using the extracted HOG features. We used a linear kernel to differentiate between the faces of different individuals.

Testing and Evaluation: We split the dataset into training and testing sets. The model was tested on unseen data to evaluate its accuracy.

Visualization: We visualized the original face images, their corresponding HOG features, and examples of correct and incorrect classifications to see how well the model performed.

![image](https://github.com/user-attachments/assets/692c193c-6fa3-4647-9faa-59829a2a5c80)

Figure 3: Correct and incorrect classifications made by the model.
