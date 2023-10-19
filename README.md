# Language Detection Model

This repository contains the code that aims to build an API with Docker that server a laguage detection model, built using scikit-learn.
The followed steps can be found in the video from Patrick Lober: https://www.youtube.com/watch?v=h5wLuVDr0oc

# The Model
The model was trained with text respected to the following languages:

Arabic,
Danish,
Dutch,
English,
French,
German,
Greek,
Hindi,
Italian,
Kannada,
Malayalam,
Portuguese,
Russian,
Spanish,
Sweedish,
Tamil,
Turkish
ChatGPT

In this regard, it is anticipated that the model will demonstrate sufficient performance in detecting the previously mentioned languages for which it was trained.


# Docker

## To build the image, run in terminal the following command:

docker build -t language-detection-app . 

docker run -p 80:80 language-detection-app
