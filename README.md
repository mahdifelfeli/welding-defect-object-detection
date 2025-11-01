# Welding Defect Object Detection using YOLOv8 🏭

This project implements a custom object detection model using **YOLOv8** to identify and localize defects in welding images. This is a common and critical task in industrial quality assurance and automated inspection.

****

---

## Overview

A YOLOv8 model (specifically `yolov8n.pt`) is fine-tuned on a custom dataset containing images of welding defects. The notebook `welding-defect-object-detection.ipynb` covers the complete workflow:

1.  **Model Loading:** Loading the pre-trained YOLOv8 nano model.
2.  **Custom Training:** Fine-tuning the model on the `welding_dataset.v1i.yolov8` dataset.
3.  **Inference & Prediction:** Running the trained model on new test images to detect defects.
4.  **Visualization:** Displaying the prediction results (images with bounding boxes and labels) using OpenCV and Matplotlib.

This solution can be used to automate the quality control process, leading to faster and more accurate defect detection than manual inspection.

---

## Tech Stack

![YOLO](https://img.shields.io/badge/YOLOv8-00467F?style=for-the-badge&logo=yolo&logoColor=white)
![Ultralytics](https://img.shields.io/badge/Ultralytics-000000?style=for-the-badge&logo=ultralytics&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)

---

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mahdifelfeli/welding-defect-object-detection.git](https://github.com/mahdifelfeli/welding-defect-object-detection.git)
    cd welding-defect-object-detection
    ```

2.  **Create a virtual environment and install dependencies:**
    ```bash
    # Create environment
    python -m venv venv
    # Activate (Windows)
    .\venv\Scripts\activate
    # Activate (macOS/Linux)
    source venv/bin/activate
    
    # Install libraries
    pip install -r requirements.txt
    ```

3.  **Download the Dataset:**
    * The dataset (`welding_dataset.v1i.yolov8`) is required to run the notebook.
    * You must download it and place it in the root of the project directory.
    * *(Note: The dataset is not included in this repository due to its size.)*

4.  **Run the Notebook:**
    * Open and run the `welding-defect-object-detection.ipynb` notebook to train the model and see the prediction results.
    ```bash
    jupyter notebook
    ```
