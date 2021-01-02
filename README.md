# Developing-Computer-Aided-Algorithm-for-the-diagnosis-in-Dermoscopic-images
## Design of a Computer Aided Diagnosis system to classify dermoscopic images whether any case belongs to Nevus or lesion. 

**System architecture**:
- Image → Normalization → Per instance standardization → Aggressive Data Augmentation → Classification. 

**Steps**:
- Data normalization,
- Per instance standardization (Standardization by mean and std of the training dataset), 
- Aggressive Data Augmentation (Rotation, Width and Height shift, Zooming, Flipping, Brightness), 
- Classification
**Best performing classification model**- Ensemble of Inception ResNetv2, Inception v3, EfficientNet B3 (ImageNet-pretrained).

Note: This project was a project of the 'Computer Aided Diagnosis' course (Master's third semester).
