# Live Attendance Tracker with Facial Recognition
### This is a project for the course (Data Science and Machine Learning) at Lighthouse Labs.

![Lou and Ryan](https://github.com/bmskarate/Finalproject_LHL/blob/main/Readme_Images/Live_feed.png?raw=true)

This attendance based software includes input feature for new users, and facial recognition feature for existing users. This implementation allows for a touchless, COVID friendly approach to taking attendance.


## Libraries and Python Version
- Python 3.8.12  
- face_recognition  
- opencv-python (cv2)  
- tkinter (GUI)  
- uuid (image name)  
- glob (img path)  
- numpy  


## Installation
Installations were done via anaconda prompt.
tkinter file will run via jupyter notebook with your conda environment


## Walkthrough
The GUI displays three options:
1. New User number - leave blank to create a random numbered folder for the new user. 
2. Number of photos - leave blank to manually collect user images (default 'p' on keyboard).
3. Add - Opens camera(0) on computer, creates new numbered folder and saves images of users face.
4. Recognize - Opens camera(0) on computer, recognizes face of user and displays name. Attendees logged to Attendance.csv file.

![main](https://github.com/bmskarate/Finalproject_LHL/blob/main/Readme_Images/program_mainscreen.png?raw=true)
![main](https://github.com/bmskarate/Finalproject_LHL/blob/main/Readme_Images/attendlog.png?raw=true)


## Future Improvements
1. Add a feature to log when user leaves and returns (break or clockout).
2. Add a feature to log when user is absent (schedule list link).
3. Add face mask detection to ensure user has their mask on properly.
4. Make alert if face is unknown (not in database).
