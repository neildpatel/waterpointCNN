# waterpointCNN
**Abstract:** Households in developing countries often rely on alternative water sources that exist outside of the datasets of public service providers. This poses a significant challenge to accurately measuring the number of households outside the public service system that use a safe and accessible water source. This paper proposes a novel deep learning approach that utilizes a convolutional neural network to detect water points in street-level imagery from Google Street View. Using a case study of the Mushin local government area in Lagos, Nigeria, preliminary results suggest that this methodology can accurately detect water points across a variety of urban settings and obstruction levels, with 93.7% precision and 88.0% recall.

This repository contains scripts for detecting public water points in urban areas of developing countries using street-level imagery obtained from Google Street View. In order to run this model, you will need the following:
- Roboflow API Key
- Google Cloud account with a Street View Static API key
- Bounded study area (I recommend restricting to a single neighborhood or ward at a time due to the time required for downloading images and running inference)

ImageDownload_GSV.ipynb: Tutorial for downloading images from GSV (developed by MIT's Sustainable Cities Lab)

ObjectDetection_GSV.ipynb: Script for deploying the object detection model from Roboflow
