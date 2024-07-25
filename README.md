# Detecting Water Points in Google Street View Imagery
<img width="1176" alt="" src="https://github.com/neildpatel/waterpointdetections/assets/125249875/83f579f1-54e3-4966-8eb4-e8f3df91da1c">

**Abstract:** Households in developing countries often rely on alternative water sources that exist outside of the datasets of public service providers. This poses a significant challenge to accurately measuring the number of households outside the public service system that use a safe and accessible water source. This paper proposes a novel deep learning approach that utilizes a convolutional neural network to detect water points in street-level imagery from Google Street View. Using a case study of the Agege local government area in Lagos, Nigeria, preliminary results suggest that this methodology can accurately detect water points across a variety of urban settings and obstruction levels, with 93.7% precision and 88.0% recall.

This repository contains scripts for detecting public water points in urban areas of developing countries using street-level imagery obtained from Google Street View. In order to run this model, you will need the following:
- Roboflow API Key
- Google Cloud account with a Street View Static API key
- Bounded study area (I recommend restricting to a single neighborhood or ward at a time due to the time required for downloading images and running inference)

**Overview**
* ImageDownload_GSV.ipynb: Tutorial for downloading images from GSV (developed by MIT's Senseable City Lab)
* ObjectDetection_GSV.ipynb: Script for deploying the object detection model from Roboflow

**More Information**
* Publication in Water Practice & Technology (July 25, 2024): https://doi.org/10.2166/wpt.2024.197
* Poster Presentation at UNC Water & Health Conference (October 25, 2023): https://neildpatel.github.io/files/Patel_UNC_Poster.pdf
* Tech Showcase at UNC Water & Health Conference (October 25, 2023): https://neildpatel.github.io/files/UNC%20Tech%20Showcase.pdf
