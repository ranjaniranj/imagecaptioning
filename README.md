# imagecaptioning-ranjani
this is a repository wherewe have developed a website which asks the user to upload and file and respective caption is generated using our model 
and the caption is displayed

│
├── README.md <- This has all the instuctions for developers using this project.
├── static
│   ├── file  <- Everytime you host the project the image you upload on the website will be stored here
│   ├── style.css <- The CSS file for our website
│ 
├── templates           
│   ├── index.html   <- Home page for our website where we upload the test image
│   ├── predict.html <- Second page which apperas when you click submit button on the home page. it displays 
│                       the corresponding captions with the image uploaded
│ 
│── app.py <- This file contains the flask commands required to run the web app
│
│── imagecaptioning_Ranjani.ipynb  <- Jupyter notebook in which we train and build our image caption generator.
│
│ Note: the three files listed below will be generated automatically when you run the ,ipynb files in your system
│
│── mine_model_weights.h5     
│
│── model.h5 
│
│── vocab.npy
│
├── dataset 
│   ├── Images               <- Code for model deployment and website design
│   ├── Flickr8k.token       <- Pretrained data for model
│
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment.
