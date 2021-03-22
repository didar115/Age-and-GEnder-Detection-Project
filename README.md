# Age-and-Gender-Detection-Project

<h1>How to use</h1>


- first create a github repository <a href="https://github.com/new">Here</a>  eg: Age Detection project
- upload the photos
- copy the project  <a href="#">HTTPS</a> url link
- then open this colaboratory site  <a href="https://colab.research.google.com/notebooks/">Here</a> 
- create a name for the project 
- clone the github repository already created by this code <a href="#">!git clone "repository url"<a>
- enter the project derectory <a href="#">%cd "project name"</a>
- import the google drive python face detection file <a href="#">!gdown https://drive.google.com/uc?id=1_aDScOvBeBLCn_iv0oxSO8X1ySQpSbIS </a>
- unzip the file  <a href="#">!unzip modelNweight.zip</a> by this code
- import the library file attached with the colab project in my repository
- for getting the out input type
 
input= cv.imread("image_name")
output= age_gender_detector(input)
cv2_imshow(output)
