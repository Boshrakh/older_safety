Repository Description
This repository contains the code and documentation for our project older safety.

Usage
To use this project for training and post-processing with YOLOv8, follow these steps:

1. Clone the repository:
git clone https://github.com/ecbme6040/e6691-2024spring-project-smod-mks2249-bk2898.git
cd Breadcrumbse6691-2024spring-project-smod-mks2249-bk2898

2. To run the yolov8s_FPN_SENet_SA:
ADD yolov8s_SENet_SA.yaml from Config folder --> in --> ultranalystics--> config--> v8 folder
Replace conv file from src folder --> in ultralytics .nn --> conv folder
3. To run postprocessing experiments:
Download the model weights from the Google Drive link provided below.
NMS: Open and execute the yolov8-NMS-visdrone.ipynb file.
SAHI: Open and execute the yolov8-SAHI-visDrone.ipynb file.
To get baseline model, open and execute the yolov8-postproc-visDrone.ipynb file.
Folder Structure
/config: Configuration files and scripts for setting up the project environment.
/src: Source code of the project required for training YOLO models and postprocessing.
E6691.2024Spring.SMOD.report.bk2898.mks2249.pdf: Detailed report of the project findings and methodology.
.ipynb files: Jupyter notebook with all the code, comments, and explanations regarding the project's analysis and results.
Dataset/Model Google Drive Link:
Dataset: link
Model weights: link
SAHI output samples: link
Important links
Students’ report - E6691.2024Spring.SMOD.report.bk2898.mks2249, link
Students’ slides - E6691.2024Spring.SMOD.bk2898.mks2249.presentation Final, link
Main reference: Ultralytics YOLOv8 (no paper) GitHub
