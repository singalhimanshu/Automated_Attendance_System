# Automated_Attendance_System

For Required Packages Run:- 

``` 
pip install -r requirements.txt 
```


When we run the train.ipynb, a window is opened that contains a notification bar and different buttons for taking images, train model and recognize the face and quit. It has following steps-

- First, the user has to enter the enrollment number & name
- Click the 'Take Image' button. After clicking the camera will open and take 60 sample images of a person and creates a dataset. It stores all the images in the 'TrainingImage' folder and makes an entry in the 'StudentDetails.csv' file
- Then click 'Train Image' button. It will train the model with the current image dataset. It will take a few seconds and put a notification 'Image Trained' in the notification bar. It creates a 'Trainner.yml' file and store in the 'TrainingImageLabel' folder.
- All the initial steps are done. Now click on the 'Track Image' button, it will open the camera and start recognizing the face. if the face is recognized then the enrollment number & name are shown on the face.
- When we press 'Q' or 'q'  the window is quit and attendance is stored in the Attendance folder in the form of a csv file with current_date and time.
- The recognized person's enrollment number & name are shown in the 'Attendance' bar.

That's how the whole software work.

## Note-

If you don't have a webcam you can use this alternative-

[Droid Cam Windows Client](https://www.dev47apps.com/droidcam/windows/)

[Droid Cam Android App](https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&hl=en_IN)
