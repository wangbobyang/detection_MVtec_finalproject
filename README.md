# detection_MVtec_finalproject
This is my final project homework, I copy by (https://github.com/SulekBartek/Anomaly_detection_MVtec/blob/master/anomaly-detection.ipynb)


Data:
MVTec dataset consists of 17 subsets including jointly 5354 images of different objects and textures. Used datasets are available on the MVTec company website (https://www.mvtec.com/company/research/datasets/mvtec-ad).


Introduction
This notebook project aims to provide an easy-to-use implementation of a simple autoencoder model for detecting anomalies on defected parts or texture images, included in the MVTec industrial dataset. Presented method is unsupervised, the model is trained on defect-free images of one of the MVTec datasets and can detect various kinds of defects in the test images.


Main libraries used in this project:
torch >= 2.0.0
torchvision == 0.14.1
numpy == 1.22

