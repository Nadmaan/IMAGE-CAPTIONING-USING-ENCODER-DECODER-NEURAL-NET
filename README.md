# Project---Image-Caption-Generator
Image caption generator is a process of recognizing the context of an image and annotating it with relevant captions using deep learning, and computer vision. This is an advanced deep learning project where more than one model must be used for analysis and preprocessing the data to obtain the results.

# Dataset Information
The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and 5 captions for each image. The features are extracted from both the image and the text captions for input. 


The features will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score is used as a metric to evaluate the performance of the trained model.

# Terminologies Used in this project
os - used to handle files using system commands.

pickle - used to store numpy features extracted

numpy - used to perform a wide variety of mathematical operations on arrays

tqdm - progress bar decorator for iterators. Includes a default range iterator printing to stderr.

VGG16, preprocess_input - imported modules for feature extraction from the image data

load_img, img_to_array - used for loading the image and converting the image to a numpy array

Tokenizer - used for loading the text as convert them into a token

pad_sequences - used for equal distribution of words in sentences filling the remaining spaces with zeros

plot_model - used to visualize the architecture of the model through different images

load_img(img_path, target_size=(224, 224)) - custom dimension to resize the image when loaded to the array

image.reshape((1, image.shape[0], image.shape[1], image.shape[2])) - reshaping the image data to preprocess in a RGB type image.

model.predict(image, verbose=0) - extraction of features from the image

img_name.split('.')[0] - split of the image name from the extension to load only the image name.


