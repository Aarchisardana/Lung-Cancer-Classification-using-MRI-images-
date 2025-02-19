
# Lung Cancer Classification on MRI Images

This machine learning project leverages a Convolutional Neural Network (CNN) to classify MRI images for lung cancer detection. The model has been trained on a dataset specifically designed for identifying lung cancer from MRI scans. Users can upload MRI images, and the model will predict whether the image indicates the presence of lung cancer.

## Project Overview

- **Model:** The Convolutional Neural Network model has been carefully designed and trained to accurately classify MRI images for lung cancer detection.
- **Dataset:** The dataset includes MRI images labeled for lung cancer detection.
- **User Interface:** Streamlit is used to create a simple and interactive user interface where users can upload MRI images and view predictions.
- **Running the Application:** To run the application, navigate to the directory containing your project files in VS Code or any other terminal. Use the following command to start the app:
  
  ```bash
  streamlit run app.py
  ```

  The dataset initially contains a total of 4,318 MRI images. To enhance the dataset, data augmentation techniques were applied, allowing the model to learn more accurately and predict results with greater precision.


