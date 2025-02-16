# Water-Bottle-Defect-Detection-Model Using YOLOv11
The Automated Quality Inspection System revolutionizes traditional quality control methods by leveraging cutting-edge robotics, 
machine learning, and computer vision to ensure efficient and accurate product inspection in dynamic manufacturing environments. 
This system integrates high-resolution camera-based fault detection on conveyor belts, enabling real-time identification of defects such 
as cracks, deformities, or inconsistencies. Once a faulty product is detected, a precision robotic arm is deployed to remove it from the 
production line, ensuring only high-quality products proceed further. Additionally, achieved an overall system precision of 91%, 
ensuring high accuracy in defect detection and improving production quality standards.

# Data Set Download
You can download the data set from the link:
https://universe.roboflow.com/visal-kroo8/defect-detection-crtff/dataset/1
Downlad the Data Set with YOLOv11 format

# Data Set Changes
Extract the Data Set and follow the format:
DataSet/


![image](https://github.com/user-attachments/assets/2ed6eb30-c685-4588-b6e0-71de7855d8d3)


# For yaml File do these changes

![image](https://github.com/user-attachments/assets/9344089f-ebae-48c6-906b-bd54b980dfeb)



       
Then create the zip of the folder

# Upload the Data Set
Upload the data to gdrive and the use google collab for Model Training
Set The Notebook settings to T4 GPU
Then follow the code file for Training of Model

# Model Results
![val_batch0_pred](https://github.com/user-attachments/assets/09f23617-db1b-4812-abec-c267ba9b98a9)
![train_batch1](https://github.com/user-attachments/assets/78b56165-68e3-446e-806e-364ef933577d)
![train_batch0](https://github.com/user-attachments/assets/288894a2-f6bd-452f-a3b4-7e568775090d)
![results](https://github.com/user-attachments/assets/ccc51ee6-6180-4655-86e3-2ad4d069af37)
![PR_curve](https://github.com/user-attachments/assets/dd7f36cd-d978-4c56-a211-3d63d3c3aa98)
![F1_curve](https://github.com/user-attachments/assets/e599d1e4-383f-44e3-8944-9cf9d3acb25e)
![confusion_matrix_normalized](https://github.com/user-attachments/assets/0c06d601-42f6-4474-bb04-3b0055b1921f)




