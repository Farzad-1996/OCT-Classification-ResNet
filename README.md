# OCT-Classification-ResNet

This project proposed a model which revolves around the
quick analysis of macular Optical Coherence Tomography (OCT)
images to distinguish three eyes related anomaly: Choroidal
Neovascularization (CNV), Diabetic Macular Edema (DME) and
accumulation of Drusen from normal OCT images of normal
patients. At first, dataset was acquired and various pre-processing
steps were performed on it. Then we splitted the dataset into
train-test-validation set with different numbers of images in each
of them. Afterward, we applied pre-trained Resnet, Inception V3,
and EfficientNet model in order to classify the images. From our
experiment, we achieved the best accuracy of 96.9% from ResNet.
Finally, we applied Explainable AI (XAI) framework in the
attempt to explain the reasons for misclassifications. Alongside
achieving the better accuracy compared to the base model, our
proposed model also explains the classification errors which can
be utilized in the future to develop better models.
