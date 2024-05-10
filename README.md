[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ifbeTrPr)
# e6691-2024Spring-project-smod-mks2249-bk2898
## Repository Description
This repository contains the code and documentation for our project ```Small Object Detection by YOLOv8```.

## Usage
To use this project for training and post-processing with YOLOv8, follow these steps:

### 1. Clone the repository:
```git clone https://github.com/ecbme6040/e6691-2024spring-project-smod-mks2249-bk2898.git``` </br>
```cd Breadcrumbse6691-2024spring-project-smod-mks2249-bk2898```

### 2. To run the yolov8s_FPN_SENet_SA:
- ADD yolov8s_SENet_SA.yaml from Config folder --> in --> ultranalystics--> config--> v8 folder 
- Replace conv file from src folder --> in ultralytics .nn --> conv folder
  
### 3. To run postprocessing experiments:
- Download the model weights from the Google Drive link provided below.
- ```NMS```: Open and execute the ```yolov8-NMS-visdrone.ipynb``` file.
- ```SAHI```: Open and execute the ```yolov8-SAHI-visDrone.ipynb``` file.
- To get baseline model, open and execute the ```yolov8-postproc-visDrone.ipynb``` file.
  
# Folder Structure
 - ```/config```: Configuration files and scripts for setting up the project environment.
 - ```/src```: Source code of the project required for training YOLO models and postprocessing.
 - ```E6691.2024Spring.SMOD.report.bk2898.mks2249.pdf```: Detailed report of the project findings and methodology.
 - ```.ipynb files```: Jupyter notebook with all the code, comments, and explanations regarding the project's analysis and results.

# Dataset/Model Google Drive Link:
 - Dataset: [link](https://drive.google.com/drive/folders/1If5C9t2I0m-cy9UFgyx1JjIm8YxP0SQZ?usp=drive_link)
 - Model weights: [link](https://drive.google.com/drive/folders/1oaV6wJ4SQHmfoO5fqyfWDv4s84Zd4sTv?usp=drive_link)
 - SAHI output samples: [link](https://drive.google.com/file/d/1jfa53t1OL_sHZa8-4DcHDjIGjGKHTtOe/view?usp=drive_link)

# Important links
- Students’ report - E6691.2024Spring.SMOD.report.bk2898.mks2249, [link](https://github.com/ecbme6040/e6691-2024spring-project-smod-mks2249-bk2898/blob/main/E6691.2024Spring.SMOD.report.bk2898.mks2249.pdf) </br>
- Students’ slides - E6691.2024Spring.SMOD.bk2898.mks2249.presentation Final, [link](https://docs.google.com/presentation/d/1PbxATgRhh-Oa-GXpqUv-f9sNErAiF_Yf-eWfQyReMbA/edit?usp=drive_link) </br>
- Main reference: Ultralytics YOLOv8 (no paper) [GitHub](https://github.com/ultralytics/ultralytics)
