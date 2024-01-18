# AUTOMATIC IMAGE CAPTIONING
by Mukul Chauhan nov,2023
</br>
</br>
 # Overview
</br>
Automatic Image Captioning is a system that generates descriptive captions for images using advanced machine learning techniques. 
</br>
This project aims to enhance the understanding and accessibility of images by providing textual descriptions, making it valuable 
</br>
for applications such as accessibility tools, content indexing, and aiding visually impaired individuals.
</br>
</br>

# Features
</br>
1.Image Caption Generation: The system utilizes state-of-the-art deep learning models to automatically generate descriptive captions for input images.
</br>
2.Pre-trained Models: Benefit from pre-trained models on large image datasets, allowing for efficient and accurate image captioning.
</br>
3.Customization: The system can be fine-tuned on specific datasets or domains to improve captioning performance for specialized applications.
</br>
4.Scalability: Designed to handle various image formats and sizes, enabling scalability for different use cases.

# Methodology
## Transfer Learning
1st. Use open source architectures like VGG16, Resnet,MobileNet or any other architectures.<br>
2nd. Remove the last few dense layers of the architecture as we dont need the softmax layer.<br>
3rd. Pass the images through the non trainable weights and store the feature matrix for each image.<br>
4th. Store the feature matrix on the harddisk to save some RAM.

## Working on Text Data
1st. Map the image to their captions in the format of dictionary.<br>
2nd. PreProcess the text data.Remove special characters. Add start and end to each comment.<br>
3rd. Tokenize the corpus and padd them to the max length of the caption.<br>


