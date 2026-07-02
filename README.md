🩺 Renal Cyst Segmentation Using U-Net and ResNet50

📖 About the Project

This project focuses on segmenting renal (kidney) cysts from CT scan images using a hybrid deep learning model that combines U-Net and ResNet50. The aim was to identify cyst regions accurately and visualize them through segmentation masks instead of simply classifying whether a cyst is present.

Along with segmentation, the project also estimates the size and location of detected cysts and presents the results using different visualization techniques.

---

🎯 Objective

The goal of this project is to automate renal cyst segmentation from CT scan images and make the detected regions easier to interpret through visual analysis.

---

🚀 Features

- CT scan image preprocessing
- Renal cyst segmentation using U-Net
- ResNet50 feature extraction
- Binary segmentation mask generation
- Otsu thresholding
- Morphological image processing
- Cyst size estimation
- Cyst location detection
- Overlay visualization on the original CT image
- Cyst size distribution analysis

---

🛠️ Tech Stack

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-image
- Pillow

---

⚙️ Project Workflow

1. Load the CT scan image.
2. Preprocess and resize the image.
3. Build a U-Net model integrated with ResNet50.
4. Generate the segmentation mask.
5. Apply thresholding and morphological operations.
6. Detect renal cyst regions.
7. Estimate cyst size and centroid location.
8. Visualize the segmentation results and analysis.

---

📊 Output

The project generates:

- Original CT scan image
- Grayscale image
- Predicted segmentation mask
- Renal cyst overlay
- Otsu threshold image
- Distance transform visualization
- Cyst size distribution graph
- Highlighted cyst region

---

💡 What I Learned

Through this project, I gained practical experience in medical image segmentation using deep learning. I learned how U-Net performs pixel-level segmentation, how ResNet50 improves feature extraction, and how image processing techniques can be used to refine segmentation results. It also helped me understand the complete workflow involved in building a medical imaging application using Python.

---

📌 Future Improvements

- Train the model on a larger medical imaging dataset.
- Improve segmentation accuracy through hyperparameter tuning.
- Extend the model to detect multiple kidney abnormalities.
- Deploy the model as a web application for real-time predictions.

---

📷 Sample Results

Add screenshots of:

- Original CT Scan
- Predicted Segmentation Mask
- Cyst Detection Overlay
- Cyst Size Distribution Graph

---

👨‍💻 Author

Aglin Beni G  
Final Year – CSE (Artificial Intelligence & Machine Learning)
