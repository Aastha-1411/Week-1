# Waste Material Classification  

## Overview  
This project focuses on classifying waste materials into two categories: **Organic** and **Recyclable**. The dataset is structured into two subfolders, representing the two classes. The project includes data preprocessing, visualization, and the implementation of both static and dynamic visualizations for distribution analysis.  

## Week 1
## Features
**- Data Collection:**
  Dataset is taken from kaggle. Link: https://www.kaggle.com/datasets/techsash/waste-classification-data/data
  
**- Data Preprocessing:**
  Efficiently loaded and labeled image data from structured folders (TRAIN\O and TRAIN\R). Applied a mapping function to enhance label clarity.  
  
**- Visualization:** 
  - Static Pie Chart: A visually enhanced pie chart with title, legend, and custom colors for better readability.  
  - Dynamic Pie Chart: Created using Plotly for interactivity, with hover tooltips displaying percentages and labels. The image of dynamic chart is uploded.

## Key Improvements  
- Automated label mapping for scalability and clarity.  
- Enhanced pie chart aesthetics with titles, legends, and custom colors.  
- Added an interactive pie chart for dynamic exploration of data.  

## Tools & Libraries Used  
- **Python**
- **Pandas**: For data manipulation.  
- **Matplotlib**: For static visualizations.  
- **Plotly**: For creating interactive charts.  
- **OpenCV (cv2)**: For image loading and processing.

  ## Week 2  
### Features 
**- Model Architecture:**  
  - Built a **CNN model** using Keras' Sequential API for **binary classification**.  
  - Added **three Conv2D layers** with ReLU activation and MaxPooling.  
  - Used **fully connected layers** with 256 and 64 neurons, ReLU activation, and Dropout (0.5).  
  - Final layer used **sigmoid activation** with **binary cross-entropy loss** and Adam optimizer.  

**- Data Preprocessing:**  
  - Used ImageDataGenerator to **rescale images** for both training and testing.  
  - Loaded image data from **structured folders** using flow_from_directory().  

**- Model Training:**  
  - Trained the model for **15 epochs** with a batch size of 64.  
  - Used validation data during training to monitor model performance.  

### Tools & Libraries Used  
- **Python**  
- **TensorFlow/Keras**: For building and training the CNN model.  
- **OpenCV (cv2)**: For image processing.  
