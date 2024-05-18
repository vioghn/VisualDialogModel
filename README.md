# VisualDialogModel
 This project presents a visual dialog system based on late fusion architecture to address image-related questions containing dialog history on the Stack Overflow platform. a data set comprising around 10,000 instances of questions has been collected, along with their corresponding correct answers, images and relevant dialogues extracted from comments. The model consists of three encoders and one decoder. The text decoder is pretrained on Ubuntu dialog dataset, which is related to computer questions, and then implemented with two language models: Pix2Struct as the image encoder and the pre-trained DialoGPT model as the textencoder-decoder.
 However, it is important to note that this project is not fully trained due to a lack of proper resources. I am still working on improving and refining the system.
