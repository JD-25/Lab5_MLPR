# Lab5_MLPR
# Lab 5: Face Detection and Clustering

## 🎯 Aim
To implement face detection using Haar Cascades and use unsupervised learning (K-Means) to cluster faces based on skin tone features (Hue and Saturation).

## ⚙️ Methodology
1. **Face Detection:** Used OpenCV's `Haar Cascade Classifier` to detect faces in the group image.
2. **Feature Extraction:** Converted the detected face regions from BGR to **HSV** color space and calculated the mean Hue and Saturation for each face.
3. **Clustering:** Applied **K-Means Clustering** (K=2) to group faces based on these skin tone features.
4. **Classification:** Detected a face in a test image (Dr. Shashi Tharoor) and predicted which cluster he belongs to.

## 📝 Conclusion
The model successfully separated the faces into two clusters based on color properties. The test image was accurately mapped to the cluster with similar lighting/skin tone characteristics.
