# xai-tumor-detection

This project aims to classify images of four different types of tumors: glioma tumor, meningioma tumor, no tumor, and pituitary tumor. The dataset consists of a total of 3000 images.

## Steps 

1. Importing Libraries:

2. Opening Folders: 
   - Checking Images: Inspecting the image folders and file structure
   - Reading Images: Loading and preprocessing the images for model training

3. Building The Model: 
   - Designing a CNN architecture for tumor classification using TensorFlow and Keras

4. Future Plans: 
   - LIME and SHAP XAI: Incorporating LIME (Local Interpretable Model-agnostic Explanations) and SHAP (SHapley Additive exPlanations) for explainability and interpretability of the model's predictions

## Usage

To run the code and reproduce the tumor classification model:
1. Install the required libraries mentioned in the "Importing Libraries" section.
2. Ensure that the image dataset is properly organized in respective folders for each tumor type.
3. Execute the code blocks sequentially, following the steps described in the "Steps Followed" section.
4. Adjust the model architecture and hyperparameters as per your requirements.
5. Run the model training process and evaluate the performance.
6. Use the trained model for tumor classification on new images or test data.

## Results and Discussion

Include a section in the README file to discuss the results, model performance, and any observations or insights gained from the project. Provide details about the accuracy or evaluation metrics achieved by the model on the test data.

## ToDo

we plan to incorporate LIME and SHAP XAI techniques to further enhance the interpretability and explainability of the tumor classification model. These techniques can provide insights into the features or regions of the images that contribute most significantly to the model's predictions.
