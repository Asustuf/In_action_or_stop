# In_action_or_stop

#1.Creating Frames.ipynb
This notebook extracts frames from a video (e.g., sample.mp4) and divides them into training and validation sets.
Frames are saved in the frames directory, with 70% used for training and 30% for validation.

#2.Training a Model and Converting into TFLite.ipynb
This notebook trains a machine learning model using the extracted frames.
The model is designed for binary classification, distinguishing between "in action" and "stop" states.
After training, the model is converted to TensorFlow Lite format for efficient deployment.

#3.Main.ipynb
The Main.ipynb notebook demonstrates how to use the trained TensorFlow Lite model for inference.
You can specify the path to an image to classify its state as "in action" or "stop."
This notebook is directly linked to Google Colab for easy inference
