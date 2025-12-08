PPE Detection with YOLOv8

This repository contains the complete project for a graduate-level computer vision course, focusing on Personal Protective Equipment (PPE) detection using the YOLOv8 architecture. The project involves training a custom object detection model to identify hardhats, masks, and persons in workplace environments to enhance safety monitoring.




🚀 Live Demo

A live web-based demonstration of the trained model is available through a Gradio interface. This allows for real-time PPE detection from a webcam feed or uploaded images.

Access the Live Demo: Gradio Web UI

Note: The Gradio link is temporary and may not be active permanently.




✨ Key Features

•
High-Accuracy Detection: Utilizes a fine-tuned YOLOv8m model to achieve a mean Average Precision (mAP@50) of 65.9%.

•
Three-Class Detection: Capable of identifying three critical classes: hardhat, mask, and person.

•
Advanced Augmentation: Employs advanced data augmentation techniques, including MixUp and Copy-Paste, to improve model robustness and generalization.

•
Comprehensive Analysis: Includes detailed Exploratory Data Analysis (EDA), model evaluation, and performance analysis.

•
Full Project Deliverables: Comes with a complete set of graduate-level project deliverables, including a final report, presentation, and a fully annotated Jupyter Notebook.




📊 Model Performance

The final model is based on the YOLOv8m architecture, which offers a strong balance between performance and computational efficiency. The model was trained for 150 epochs on a custom dataset, achieving the following performance metrics:

Metric
Value
mAP@50-95
46.8%
mAP@50
65.9%
Precision
96.1%
Recall
62.7%
Inference Speed (NVIDIA L4)
31 FPS


These results represent a +13.2% improvement in mAP@50 compared to the baseline YOLOv8n model, demonstrating the effectiveness of the tuning and training strategy.




🗂️ Dataset

The model was trained on a challenging dataset of 7,523 images, containing annotations for the three target classes. The dataset exhibits a significant class imbalance, with the person class accounting for only 2.28% of instances, which presented a key challenge addressed during model training.




🛠️ Technology Stack

•
Framework: YOLOv8 (Ultralytics)

•
Programming Language: Python

•
Key Libraries: PyTorch, OpenCV, Pandas, Matplotlib, Seaborn

•
Environment: Google Colab (with NVIDIA L4 GPU)

•
Deployment: Gradio




deliverables

This project includes three main deliverables:

1.
Final Project Report: A comprehensive 20-30 page report in APA 7 format, detailing the project's methodology, results, and discussion.

2.
Presentation Deck: A 12-slide presentation suitable for a 10-12 minute video recording, outlining the project's key aspects.

3.
Jupyter Notebook: A detailed notebook (PPE_Detection_YOLOv8_v10.ipynb) that covers the entire project lifecycle, from EDA to model training and evaluation.




⚙️ Installation and Usage

To run this project locally, follow these steps:

1.
Clone the repository:

Bash


git clone <repository-url>




2.
Set up the environment: It is recommended to use a virtual environment. The required packages are listed in the Jupyter Notebook.

3.
Open the Jupyter Notebook: Launch Jupyter Notebook and open PPE_Detection_YOLOv8_v10.ipynb.

4.
Run the cells: Execute the cells in the notebook to perform data analysis, model training, and evaluation.




👥 Team

•
Faisal Abdul Gaffoor: Team Lead & ML Engineer

•
Balaji K. C. Kumaresan: Data Analyst & Tech Writer




📄 License

This project is licensed under the MIT License. See the LICENSE file for more details.

