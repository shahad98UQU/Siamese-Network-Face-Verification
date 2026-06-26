# Face Verification & Similarity Metrics via Siamese Neural Networks (SNN)

## Project Description
This repository delivers an implementation of a Siamese Neural Network (SNN) designed for verification and recognition tasks. Instead of standard classification, the architecture features twin subnetworks with shared weights to output precise distance embeddings for similarity matching.

## Architecture & Technical Summary
* **Subnetwork Layout:** Two identical convolutional layers processing dual stream inputs simultaneously to compute dense feature vectors.
* **Metric Optimization:** Measures similarity via Euclidean distance metrics; features implementation paths exploring Contrastive Loss and Triplet Loss optimization.
* **Advanced Strategies Included:** Theoretical and practical optimization layouts including Hard Positive/Negative Mining to strengthen boundary distances between deceptively similar classes.

## Frameworks & Tools
* Python
* PyTorch / torchvision
* Matplotlib & NumPy
* Jupyter Notebook
