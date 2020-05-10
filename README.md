# Capstone_Project
Deep Learning Models in detecting pathologies in chest X-rays

Important Links - 

1. Pathology detection using Chest X-rays
-  NIH dataset = 112120 chest x-rays with 14 pathology labels from https://nihcc.app.box.com/v/ChestXray-NIHCC
2. NIH Chest X-rays - Over 112,000 Chest X-ray images from more than 30,000 unique patients
-  https://www.kaggle.com/nih-chest-xrays/data
-  Sample data - https://www.kaggle.com/nih-chest-xrays/sample
3. Github 
-  https://github.com/mlmed/dl-web-xray
4. Intelligence-Based Medicine
-  https://www.journals.elsevier.com/intelligence-based-medicine/
5. COVID-19 dataset 
-  https://github.com/ieee8023/covid-chestxray-dataset/tree/master/images

Sample Dataset Description - 

- sample.zip: Contains 5,606 images with size 1024 x 1024

- There are 16 classes (15 diseases, and one for "No findings") in the full dataset, but since this is drastically reduced version of the full dataset, some of the classes are sparse with the labeled as "No findings"

1) Hernia - 13 images
2) Pneumonia - 62 images
3) Fibrosis - 84 images
4) Edema - 118 images
5) Emphysema - 127 images
6) Cardiomegaly - 141 images
7) Pleural_Thickening - 176 images
8) Consolidation - 226 images
9) Pneumothorax - 271 images
10) Mass - 284 images
11) Nodule - 313 images
12) Atelectasis - 508 images
13) Effusion - 644 images
14) Infiltration - 967 images
15) Covid-19 - "Yet to add"
16) No Finding - 3044 images

- sample_labels.csv: Class labels and patient data for the entire dataset

1) Image Index: File name
2) Finding Labels: Disease type (Class label)
3) Follow-up #
4) Patient ID
5) Patient Age
6) Patient Gender
7) View Position: X-ray orientation
8) OriginalImageWidth
9) OriginalImageHeight
10) OriginalImagePixelSpacing_x
11) OriginalImagePixelSpacing_y
