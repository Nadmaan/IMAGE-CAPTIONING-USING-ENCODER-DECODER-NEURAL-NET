Image caption generator is a process of recognizing the context of an image and annotating it with relevant captions using deep learning, and computer vision. This is an advanced deep learning project where more than one model must be used for analysis and preprocessing the data to obtain the results.

# Dataset Information
The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and 5 captions for each image. The features are extracted from both the image and the text captions for input. 

The features will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score is used as a metric to evaluate the performance of the trained model.

# Steps in execution of the project
**1. Import Modules**

![dependencies](https://user-images.githubusercontent.com/83595856/185237547-ada7df51-4d8f-4045-8bd6-d0f67d41be24.jpg)

**2. Model Creation**

**VGG-16 for encoding** 

![vgg-16](https://user-images.githubusercontent.com/83595856/185238237-e79fc414-9df5-4d35-baae-ada4e571ed89.jpg)

**Encoding Vocabolary**

![Embedding](https://user-images.githubusercontent.com/83595856/185238624-bcdfa28f-f6bf-47df-9b04-344f16784f1b.jpg)

**LSTM for Decoding**

![LSTM_main](https://user-images.githubusercontent.com/83595856/185239101-80c8378b-8f8a-4afa-9d5e-fc6eda785795.jpg)

![LSTM](https://user-images.githubusercontent.com/83595856/185239266-ff0fec80-0415-4e01-9303-ee459b16964a.jpg)

**3. Validate the data using BLEU Score**

![image](https://user-images.githubusercontent.com/83595856/185239495-0578d499-31ec-4d34-8b43-9b70ed51f3fd.png)

BLEU Scores

![BLEU-2](https://user-images.githubusercontent.com/83595856/185239660-67b9ad21-c1c4-4187-8afa-f1f9916bb264.jpg)

**4. Visualize the Results**

![Results images](https://user-images.githubusercontent.com/83595856/185239975-e1525185-e423-4607-b5d4-22cf90e6977e.jpg)

**Achieved a BLEU score of 0.513** 





