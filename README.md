# Weed Object Detection Model
## Introduction

Weeds are a constant headache for the occasional gardener. Weeds compete with more desirable plants for moisture, sunlight and nutrients in lawns, garden beds and vegetable patches alike. Weed control costs gardener's countless hours, and millions of dollars, each year. For the amateur gardener it can be difficult to identify a weed species and know what action to take. How handy would it be to take a photo of an unknown weed in the garden and be provided with information on options to control it? 

This project aims to use computer vision techniques to correctly identify and classify weeds in an image to allow gardeners to take appropriate action to control weed species.

## Dataset
The original dataset can be found [here](https://weed-ai.sydney.edu.au/datasets/2c14915b-0827-4b65-9908-d2a6df0d48f3). The dataset is named CottonWeedDet12 and comprises 5,648 colour images of weeds that are common to cotton fields in the southern US. For this project the dataset was modified with images resized to be 1280 x 720 and annotations updated to match the resized images. The updated dataset used in this project can be found [here](https://app.roboflow.com/deep-learning-assignment-ewyc5/weed-detection-d7dau/5). The dataset is licenced under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Models
The following models are considered as part of this project:
- Faster RCNN, and
- Yolov7.
