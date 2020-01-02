# Image-classification-using-deep-learning

People rarely train deep neural networks from scratch (with random initialization) these days. Instead, we often use some form of transfer learning, which uses a pretrained network to save training time and improve model prediction. In this assignment, we will explore and compare two widely-used transfer learning techniques: feature extraction and fine-tuning.

Before You Start

Please make sure you have numpy, Keras and one of its backend engines (e.g., TensorFlow).

Dataset and Task

We will use the Viziometrics dataset (paper1, paper2). The dataset contains 15k+ images from scientific publications that are hand-labeled as one of the five classes: equation, photo, scheme, table, and visualization. The train, validation, and test set has already been splitted for us. Our task is to train neural network classifiers to predict the five labels.

How to Complete This Assignment and What to Turn In

We have provided some starter code. Each task you need to complete is marked with a red school bag 🎒and is worth a few points. Each task will either ask you to print something or report certain metrics. Please submit your completed notebook with the code and the required output of each task. You will not receive full points if either code or output is missing.

👉 Please start early. It takes time to train these networks.
