

# Face_Generation

Face_Generation project is a part of DEEP LEARNING nano degree of UDACITY. In this project, I generated new images of faces that look as realistic as possible!
The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

# Project Execution and Dependencies

 1) Clone the repository and navigate to the downloaded folder.
 
     ``` python
     git clone https://github.com/shankar939014/Generate_Faces.git
     
     ```
 
 2) If you have GPU, train the DCGAN network using the same else it is recommended to use Cloud service suchs as AWS, GCP. They are providing
     Virtual Machines with pre installed libraries and frameworks. I have taken aws p3.2x instance which is having pytorch 0.4 with cuda 9.
     
 3) We can download the Dataset by clicking the link below. 
 
    [Download  CelebFaces Attributes Dataset (CelebA)]( https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)
 
 4) Open the jupyter notebook dlnd_face_generation.ipynb
  
      ```
      jupyter notebook dlnd_face_generation.ipynb
      
      ```
 5) Model got trained for 30 epochs with learning rate of 0.0004 and samples are collected and saved as train_sample.pkl at the end of each epoch.
 
 6) Below are the sample faces generated with the trained DCGAN.
   ![alt text](https://github.com/shankar939014/Generate_Faces/Celeb_Faces.JPG "Logo Title Text 1")
  
