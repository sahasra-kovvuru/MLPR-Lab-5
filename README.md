# MLPR-Lab-5
AIM: The aim of this experiment is to detect faces in an image using a Haar Cascade classifier, extract colour based features such as saturation and hue from detected faces, and group them using K-Means clustering to analyze similarities and classify a template face based on its cluster.

METHODOLOGY: 
1) Face Detection
- Load the faculty group image
- Convert it to grayscale
- Use a Haar Cascade classifier to detect faces

2) Feature Extraction
- Convert detected face regions to HSV colour space
- Extract Hue and Saturation values
- Use the mean hue and saturation as features

3) Clustering
- Apply K-Means clustering on hue–saturation features
- Group faces into clusters based on colour similarity
- Visualize clusters and centroids using scatter plots

4) Template Face Classification
- Load the template image
- Detect the face and convert it to HSV
- Extract hue–saturation features
- Predict its cluster using the trained K-Means model
- Plot the template face on the cluster visualization

KEY FINDINGS:
- Haar Cascade successfully detected faces in the group image
- Hue–Saturation features provide a simple way to represent facial colour information
- K-Means clustering grouped faces with similar colour characteristics
- The template face was classified into the closest cluster based on its colour features

PLOTS: 






