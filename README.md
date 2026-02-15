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

<img width="953" height="599" alt="faces" src="https://github.com/user-attachments/assets/b2a3a6c0-aae0-454f-9b6d-0d59643d7e06" />
<img width="1358" height="739" alt="image" src="https://github.com/user-attachments/assets/3e6b0a74-40e7-4c32-a692-6f100d2fa3de" />
<img width="1354" height="730" alt="image" src="https://github.com/user-attachments/assets/c152bd01-e542-4334-943b-87edd32c0d21" />
<img width="296" height="318" alt="shashi tharoor" src="https://github.com/user-attachments/assets/bd65f2c2-bd4f-4a1a-8ee2-4713d4314233" />
<img width="1350" height="732" alt="image" src="https://github.com/user-attachments/assets/fa584776-543b-4417-a3f3-8f3cb45459ec" />
<img width="1350" height="728" alt="image" src="https://github.com/user-attachments/assets/ef25effe-91e4-4dde-a35f-c3d026cfa3a9" />









