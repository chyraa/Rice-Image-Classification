# Rice Image Classification Project

This is a **Rice Image Classification Project** that utilizes a rice image dataset categorized by class. Various machine learning and image processing techniques are applied to classify images into predefined categories.

### **Project Description**
1. **Objective**: Develop an image classification model capable of identifying and categorizing rice images based on their visual features.
2. **Dataset**: The dataset used consists of rice grain images from Kaggle, featuring a variety of shapes and colors.
3. **Data Processing Techniques**:
   - Utilizes Python libraries such as NumPy, Pandas, and Sklearn for data manipulation.
   - Image processing with Skimage and OpenCV.
   - Image augmentation to enhance model performance.
4. **Models Used**:
   - Models built with **TensorFlow and Keras**, including popular architectures like MobileNet and DenseNet121.
   - Application of **Convolutional Neural Networks (CNN)** for visual feature extraction.
5. **Model Evaluation**:
   - Dataset is split into **training and testing sets** to evaluate performance.
   - Uses **evaluation metrics** such as confusion matrix and classification report to analyze results.

## How to Use

Here are the steps to run the **Rice Image Classification** project on Google Colab:

### **1. Initial Setup**
- Ensure you have a Google account and are signed into Google Colab.
- **Open the Colab project** via the following link: [Rice Image Classification Project](https://colab.research.google.com/drive/1plhq93FQ4SSqxcq7LEjibzZo916LV6o1#scrollTo=U4cU5-P9wzbF).
- Make sure GPU is enabled by going to **Runtime** → **Change runtime type** → **Hardware accelerator** → select **T4 GPU**.

### **2. Install and Import Libraries**
- Run the cell **"Import All Required Libraries"** to import all dependencies like NumPy, Pandas, TensorFlow, and Skimage.
- Ensure all required packages are installed.

### **3. Data Preparation**
- **Upload the dataset** if not already available using the cell with `files.upload()`.
- The dataset will be processed and split into **training and test sets** using `train_test_split`.

### **4. Model Building and Training**
- A **CNN-based model** will be built using architectures like **MobileNet** or **DenseNet121**.
- Use `ImageDataGenerator` for data augmentation.
- Start training the model using `model.fit()` with the preprocessed dataset.

### **5. Model Evaluation**
- Use **confusion matrix** and **classification report** to assess model performance.
- Run the evaluation cell using `model.evaluate()` to check accuracy.

### **6. Image Prediction**
- Upload a new image to test.
- Use `model.predict()` to get the classification result.
- Visualize the output using `plt.imshow()` and predicted label.
