# CaltechCapstoneProject
EdTech: Video Quality Assessment Project
1. Introducion:
The purpose of this project is to assess the quality of E-Learning videos available on YouTube. The project 
involves the use of various techniques and models to analyze different aspects of the videos, including 
instructor presence, visual aids, and object detecƟon. The project aims to idenƟfy key factors that 
contribute to engaging and effecƟve video content.
2. Data CollecƟon:
To gather data, a playlist library was uƟlized to download the E-Learning videos from YouTube. The 
downloaded videos served as the dataset for further analysis. 
3. Feature ExtracƟon with VGG16:
A pre-trained VGG16 model was employed for feature extracƟon from the videos. These features served 
as a basis for subsequent analysis and clustering. 
4. Clustering with KMeans: 
To group similar videos together, the KMeans algorithm was applied to the extracted features. This 
allowed for the idenƟficaƟon of clusters based on shared visual aƩributes. 
5. Body Keypoint DetecƟon with MediaPipe:
MediaPipe, a powerful framework, was uƟlized to detect body keypoints in the E-Learning videos. By 
idenƟfying the posiƟons of key body joints, such as elbows, wrists, and knees, it became possible to 
assess the instructor's body language and movements. This analysis provided insights into the 
instructor's effecƟveness in conveying concepts and engaging with the audience.
6. Text DetecƟon with EAST Model:
The EAST text detecƟon model was employed to detect and analyze text elements within the E-Learning 
videos. By idenƟfying text regions, the model facilitated an assessment of the quality and relevance of 
textual informaƟon displayed on slides or whiteboards. 
7. Face DetecƟon with Haar Cascade Classifier:
To assess the presence and engagement of instructors, a Haar cascade classifier model was uƟlized to 
detect faces in the video frames. 
8. Human DetecƟon with Pre-Trained TensorFlow Model: 
A pre-trained TensorFlow model was used to detect human figures within the videos. This analysis aimed 
to evaluate the instructor's movements and interacƟons within the video frames. 
9. SenƟment Analysis on Video Comments:
The project also incorporated senƟment analysis of video comments. The comment dataset generated 
from the this tasks was deployed in Amazon SageMaker, a powerful machine learning plaƞorm, to 
perform senƟment analysis and determine the senƟment (posiƟve, negaƟve, neutral) of viewer 
comments. 
10. Conclusion: 
Through the integraƟon of various techniques and models, this project successfully assessed the quality 
of E-Learning videos available on YouTube. By analyzing instructor presence, visual aids, and object 
detecƟon, valuable insights were obtained regarding engaging and effecƟve video content.
