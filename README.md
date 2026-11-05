CNN BASED ATTENDANCE SYSTEM

# CNN-Based Face Recognition Attendance Management System

This project aims to develop an automated attendance management system using **MTCNN, CNN, and SQL**.

The system uses **MTCNN (Multi-task Cascaded Convolutional Networks)** to detect and extract faces from images, followed by a **CNN-based face recognition model** to identify individuals based on their facial features. The attendance records, including student details and timestamps, are stored and managed using an **SQL database**.

The primary objective is to build a reliable, efficient, and automated attendance system that minimizes manual intervention, prevents proxy attendance (buddy punching), and maintains accurate attendance records.

The entire project is being developed and documented from scratch, covering the fundamentals, implementation, model development, database integration, and evaluation.


# Dataset Collection
Data is the foundation of any face recognition system. Before building and training our model, we need a properly structured facial image dataset containing multiple identities and sufficient variations in facial appearance, orientation, lighting, and expressions.
Recommended Datasets
1. Face Recognition Dataset-Contains facial images of famous peoples across the globe
2. CASIA-WebFace – A large-scale facial recognition dataset containing multiple identities and facial images.
3. VGGFace2 – Contains facial images with variations in pose, age, and illumination

For our attendance management system, the dataset should ideally contain:
- Multiple images per individual.
- Different facial orientations and expressions.
- Variations in lighting conditions.
- Clearly identifiable facial images.
- Proper identity labels for supervised learning.

 # Our Approach
We will initially explore publicly available datasets to understand facial image preprocessing, face detection using MTCNN, and CNN-based feature extraction.

Later, we will collect and organize our own student facial image dataset for identity recognition and attendance management.
so we have to work on group dataset from nowonwords


