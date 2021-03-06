# Age-and-Gender-Detection-with-opencv  <img alt="Plugin on redmine.org" src="https://img.shields.io/redmine/plugin/stars/redmine_xlsx_format_issue_exporter">

### Objective :
![face and gender with Ai](https://user-images.githubusercontent.com/75518471/142719031-f424a5ac-d943-47fa-9b9e-df044caf1ef5.jpg)

To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.
##

### About the Project :
In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. I used the models trained by Tal Hassner and Gil Levi. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.

##

### Dataset :
For this python project, I had used the Adience dataset; the dataset is available in the public domain and you can find it here. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from Flickr albums and distributed under the Creative Commons (CC) license. It has a total of 26,580 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 1GB in size. The models I used had been trained on this dataset.

##

#### Additional Python Libraries Required :
- OpenCV
 - pip install opencv-python
- argparse
 - pip install argparse
 ##
#### The contents of this Project :
ope- ncv_face_detector.pbtxt
- opencv_face_detector_uint8.pb
- age_deploy.prototxt
- age_net.caffemodel
- gender_deploy.prototxt
- gender_net.caffemodel
- a few pictures to try the project on
- detect.py
##
Usage :
Download - my Repository

Open your Command Prompt or Terminal and change directory to the folder where all the files are present.
- Detecting Gender and Age of face in Image Use Command :
      python detect.py
- Press Ctrl + C to stop the program execution.
##
## Working:
NOTE:- I downloaded the images from Google,if you have any query or problem i can remove them, i just used it for Educational purpose
python detect.py --image girl1.jpg<br>
Gender: Female<br>
Age: 25-32 years<br>
<br><br>

##

![Detecting age and gender girl1](https://user-images.githubusercontent.com/75518471/142718398-4c7300fe-e673-49ab-90f1-fdccf876f825.png)
<br><br>
##
<br><br>
#
python detect.py --image kid1.jpg<br>
Gender: Male<br>
Age: 4-6 years<br>
<br><br>
![Detecting age and gender kid1](https://user-images.githubusercontent.com/75518471/142718408-f92df664-15bc-494c-9089-34ec0041d462.png)
 
 <br><br>
 ##
 
python detect.py --image woman1.jpg<br>
Gender: Female<br>
Age: 38-43 years<br>
<br><br>
![Detecting age and gender woman1](https://user-images.githubusercontent.com/75518471/142718410-a4f4d587-2602-495e-96e3-b6c1913cd414.png)

## That's it
