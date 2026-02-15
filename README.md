# Lab5_MLPR
# Lab 5: Face Detection and Clustering

## Aim
To implement face detection using Haar Cascades and use unsupervised learning (K-Means) to cluster faces based on skin tone features (Hue and Saturation).

## Methodology
1. **Face Detection:** Used OpenCV's `Haar Cascade Classifier` to detect faces in the group image.
2. **Feature Extraction:** Converted the detected face regions from BGR to **HSV** color space and calculated the mean Hue and Saturation for each face.
3. **Clustering:** Applied **K-Means Clustering** (K=2) to group faces based on these skin tone features.
4. **Classification:** Detected a face in a test image (Dr. Shashi Tharoor) and predicted which cluster he belongs to.

## Conclusion
The model successfully separated the faces into two clusters based on color properties. The test image was accurately mapped to the cluster with similar lighting/skin tone characteristics.

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/d73b4f38-b4ab-4497-86ac-54cdb21bed19" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/8b4c8615-a543-4048-b4f9-9c4497674650" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/d513a582-d0b4-4ff0-8c2c-434f199145e3" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/52142ac6-b118-4cb5-9abd-414c3cb1fc3a" />
