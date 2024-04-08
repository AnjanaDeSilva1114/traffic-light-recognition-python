# Traffic Light Recognition SVM vs CNN Python

## Instructions to Runs the Program

This program is developed using VS Code, so please utilize VS Code software to execute it. The code provided in this appendix is divided into several sections because it was originally created using an IPython Notebook (Jupyter Notebook – file type: ipynb). You are welcome to run it using Python alone or recreate the Jupyter Notebook environment.

To run the provided code, you'll need to follow these instructions. Please make sure you have Python 3.11.6 installed on your system.

### Step 1: Install Required Libraries

Ensure you have the necessary libraries installed. You can install them using pip, a package manager for Python. Open your command line interface and execute the following command:
Eg: pip install numpy matplotlib OpenCV-python scikit-image TensorFlow.
All the required libraries as follows:
* NumPy
* OpenCV
* Matplotlib
* scikit-image
* TensorFlow

### Step 2: Prepare the Dataset

Ensure you have the dataset organized as described in the code. For the SVM model, you should have images of traffic lights cropped and categorized into different directories based on their colors (e.g., Green, Red, Yellow). 
Note: For CNN model to be trained you should have images of traffic lights cropped and categorized into different directories based on the number of 0, 1, 2 in order with Green Red and Yellow)

### Step 3: Train the Model

Run the code segments responsible for training the model on the prepared dataset. Ensure you adjust any paths or configurations as needed to match your setup.

### Step 4: Save the Trained Model

Once the model is trained, save it using the provided code segment.

### Step 5: Load and Run the Model

Load the trained model using the provided code and execute the function to predict the color of a traffic light in each image. Make sure to provide the correct path to the image you want to analyze.

###Step 6: Verify Results
Verify the predicted traffic light color printed by the code matches the actual color of the traffic light in the image displayed.
Additional Notes:
* Make sure the dataset directories and image paths are correctly specified in the code.
* Ensure the paths for saving and loading the model match your directory structure.
* Adjust any hyperparameters or configurations as needed based on your dataset and requirements.

By following these steps, you should be able to run the provided code successfully and predict the color of traffic lights in images using the trained SVM and CNN models.

