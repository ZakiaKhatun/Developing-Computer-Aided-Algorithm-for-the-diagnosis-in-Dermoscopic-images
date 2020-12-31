# Developing-Computer-Aided-Algorithm-for-the-diagnosis-in-Dermoscopic-images-to-classify-melanoma-vs-
## Design of a Computer Aided Diagnosis system to classify dermoscopic images whether any case belongs to Nevus or lesion. 

**System architecture**:
- Image → Normalization → Per instance standardization → Aggressive Data Augmentation → Classification. 

**Steps**:
- Data normalization,
- Per instance standardization (Standardization by mean and std of the training dataset), 
- Aggressive Data Augmentation (Rotation, Width and Height shift, Zooming, Flipping, Brightness), 
- Classification
**Best performing classification model**- Ensemble of Inception ResNetv2, Inception v3, EfficientNet B3 (ImageNet-pretrained).

Note: This project was the project of the third semester of my master's in the 'Computer Aided Diagnosis' course.
