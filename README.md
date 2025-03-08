I have used Convolutional Neural Network(CNN) using deep learning techniquest to predict the gender of the person in the image.

I have used OpenCV library for image processing: To normalize the imput date

Detected and sliced the face of the person in the image
Converted the images to grayscale
Reshaped the images to 48 x 48 input size
Model is trained on 5 hidden layers with 1,102,902 Trainable parameters

This repo consists of 2 .ipynb files -

Gender-Prediction-Model.ipynb - For Training and evaluation of the model and saved the model
Testing-Model-with-Image.ipynb - For image processing of test image and predicting the gender of the person in image using saved model from above
I have highlighed the cases where model is going wrong in predicting the gender of the person in image. These are all the cases where the person in the image is kid. For kids even we as humans cannot define the gender of the kid by looking at face.

I have used the libraries -

OpenCV for image processing
FER for face detection
Matplotlib to load and process image data
numpy to process image data in the form of numpy arrays
Keras for model building and saving the model
Gender prediction models using image processing can be applied in several real-time scenarios, including:

Surveillance Systems: Analyzing video feeds for demographic insights in public spaces, helping to monitor and manage crowd behavior.
Retail Environments: Understanding customer demographics in stores to optimize layouts, product placements, and marketing strategies based on the predicted gender of shoppers.
