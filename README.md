Shape Detection and Processing
==============================

Welcome to the Shape Detection and Processing project! This project is divided into three main sections: **Isolation**, **Fragmented**, and **Occluded** shapes. Each section contains specific tasks related to detecting and processing 2D shapes from curves. The project focuses on developing algorithms for identifying and analyzing various geometric shapes in different scenarios.

Project Structure
-----------------

-   **Isolation:** Identifying regular shapes in a given set of curves.
-   **Fragmented:** Identifying the presence of symmetry in closed shapes.
-   **Occlusion:** Completing curves with gaps or partial holes due to occlusion removal.

Getting Started
---------------

To run the code and explore the tasks, you can use the following link:

[Run on Google Colab](https://colab.research.google.com/drive/1tm2ybxmG0Pe2BCVxFq2YYwwBEjNdrabn?usp=sharing)

Sections Overview
-----------------

### 1\. Isolation

The Isolation section leverages the `ShapeDetector` class, a Python tool designed to detect and classify various geometric shapes from a set of 2D points. This class is capable of identifying circles, rectangles, stars, lines, and ellipses from given path data. Additionally, it offers functionalities to merge similar shapes, update paths based on detected shapes, and visualize the results.

### 2\. Fragmented

The Fragmented section uses the `SymmetryFinder` class to detect and visualize symmetry in 2D polygonal paths. This class provides methods for identifying vertical, horizontal, and general symmetry lines, as well as the center of radial symmetry within a given set of 2D paths.

### 3\. Occlusion

The Occlusion section is divided into two subparts: **Connected Occlusion** and **Disconnected Occlusion**.

#### **Connected Occlusion**

The `ConnectedOcclusion` class is designed to process a set of 2D paths, identifying common points between them, generating smooth curves that connect these points, and modifying the paths accordingly. This class also allows for the visualization of both the original and modified paths, and provides functionality to save the modified paths to a CSV file.

#### **Disconnected Occlusion**

The `Disconnected_Occlusion` class focuses on processing and analyzing image data using a pre-trained ResNet50 model for feature extraction. This part of the project is aimed at identifying the nearest image in a dataset by calculating the Euclidean distance between the features of an input image and the images in the dataset. Additionally, this class provides functionality for reading and processing path data from a CSV file and visualizing it.
