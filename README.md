# Dental X Ray Diagnosis using Deep Neural Networks
### Project Intro/Objective:
The main motto of our project is to detect dental diseases from x-rays by using Deep learning neural networks.This will be helpful for dentist to predict disease easily.Images are being fed as input to our web appilication and we get number as output that tells disease.

### Abstract
Artificial intelligence, Deep learning algorithms have captivated the healthcare industry as these innovative analytics strategies become more accurate and applicable to a variety of tasks. In the field of Medical Sciences, we have large scope for data science applications in dentistry.  Dental X-rays (radiographs) are images of teeth that dentist uses to evaluate the oral health. This can help your dentist to identify problems like cavities, tooth decay, and impacted teeth. As it is becoming a hectic work for the dentists to check these radiographs and tell the result, we came up with a deep learning model which identifies and predict the diseases like jaw disorders, cysts, tumours etc. and makes it easier and faster for the dentists. It predicts the dental diseases by scanning the Radiographs, enabling the dentists   to do the treatment fastly. This model includes an automatic method with the medical knowledge, the images are fed as input to the deep learning model. After the training is over for all the dental related diseases, we then use it for testing purpose which predicts dental diseases.
### Technologies used
1)Python<br />
2)Keras<br />
3)HTML<br />
4)CSS<br />

### Tools Required

1)Anaconda-Jupyter Notebook.<br />
2)Google Collab

### Prerequisites

1)Python Programming<br />
2)Machine Learning,Deep Learning basic modules

### Modules


### Installing
Step1:
Data collection:<br />
X-ray dental images data set is being collected obtaining in form of .pano format.<br />
Step2:
Data preprocessing:<br />
Data  is need to be preprocessed.x-rays are converted into jpeg format and classification of images is done accoring to whether an image having caries or not.<br />
Step3:
Loading data:<br />
Google collaboratory labs is used for training and prediction.classified data is being loaded by zipping classified data.Training data set as well as Validation dataset is given and uses Keras as module.<br />
Step4:
Applying model:<br />
Deep learning uses transfer learning which is having predefined architectures that used for  evaluation.Here mobile net architecture is used.
Mobile net architecture is being appilied on dataset that is obtained from keras module.Here activation function is sigmoid used.
Loss function as binary crossentrophy which represents binary classification yes or not."sgd" is optimizer used.Model has given good accuracy. Model is saved.<br />
Step5:
Testing model:<br />
PIL and io as modules used for image input .Model is tested by giving an input image to it which uses Matplotlib as module and image preprocessing also performed uses cv2.<br />
Step 6:
Prediction:<br />
Prediction given best results for an given x-ray,value obtained is between 0 and depending on value disease is predicted.<br />
step 7:
Developing an Web appilication:<br />
Web appilication is being developed using Scripting language javascript and technologies like HTML and CSS.Input image is taken through local files and prediction output is given as value that tells whether a presons x-ray is having caries or not. 


## Running the tests







## Deployment

1)Collect the labelled Dataset.<br />
2)Follow the steps in the dentalp.pynb file to get the model.<br />
3)Download the dentalalpha.h5<br />
4)Now,for a web app the model is uploaded into server i,e., Predictapp.ipynb<br />
5)Predict.html acts as client and contains all the UI of the webpage.<br />

## Contributing Members:
Team Lead:Susmitha Patchigolla<br />
Other members:<br />
Namratha Mummaneni<br />
Haripriya Vadlapatla<br />


