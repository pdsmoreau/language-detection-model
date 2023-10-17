# Language Detection Model

This repository contains the code that aims to build an API with Docker that server a laguage detection model, built using scikit-learn.
The followed steps can be found in the video from Patrick Lober: https://www.youtube.com/watch?v=h5wLuVDr0oc

# Docker

docker build -t language-detection-app . 

docker run -p 80:80 language-detection-app