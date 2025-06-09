This repository contains the code, report, and resources for the AI for AgriTech Hackathon Phase 1 submission. The project develops a Convolutional Neural Network (CNN) to classify potato leaf images into three categories: Early Blight, Late Blight, and Healthy.

## Project Overview
- **Authors**: Nikhil Teja Cheema (MTech IIT Hyderabad), N S Deepika (PhD IIT Hyderabad)
- **Objective**: Classify potato leaf images to identify diseases using a dual-branch CNN.
- **Test Accuracy**: 93.33%

## Repository Contents
- `model.py`: Python script for data preprocessing, model architecture, training, and evaluation.
- `report.tex`: LaTeX source file for the project report.
- `report.pdf`: Compiled PDF of the project report (if you’ve compiled it).
- `images/`: Folder containing images used in the report (e.g., confusion matrix heatmap, training plots, sample images).

## Dataset
The dataset comprises 1500 potato leaf images (500 per class: Early Blight, Late Blight, Healthy). Due to GitHub’s file size limits, the dataset is hosted on Google Drive. [Download the dataset here]((https://drive.google.com/drive/folders/1GFvtfL94rGrPQDkMDNDjgmI41wvPpytL?usp=sharing)).

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/NikhilTeja5/Potato-Disease-Classification-Hackathon.git

2. Install dependencies:
pip install -r requirements.txt

3. Download the dataset from the link above and place it in the appropriate directory.

4. Run the script:
python model.py


##Report
The project report (report.pdf) includes:
   > Introduction and dataset description
   > Model code and architecture
   > Evaluation metrics (accuracy, precision, recall, confusion matrix)
   > Optimization techniques and conclusion

