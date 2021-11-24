# Live Attendance Tracker with Facial Recognition
### This is a project for the course (Data Science and Machine Learning) at Lighthouse Labs.

![Lou and Ryan](http://github.com/bmskarate/final_project_LHL/Readme_images/Live_feed.png)

This attendance based software includes input feature for new users, and facial recognition feature for existing users. This implementation allows for a touchless, COVID friendly approach to taking attendance.


## Libraries and Python Version
Python 3.8.12
face_recognition
opencv-python (cv2)
tkinter (GUI)
uuid (image name)
glob (img path)
numpy


## Installation
Installations were done via anaconda prompt.
tkinter file will run via jupyter notebook with your conda environment


## Walkthrough
The GUI displays three options:
1. New User number - leave blank to create a random numbered folder for the new user. 
2. Number of photos - leave blank to manually collect user images (default 'p' on keyboard).
3. Add - Opens camera(0) on computer, creates new numbered folder and saves images of users face.
4. Recognize - Opens camera(0) on computer, recognizes face of user and displays name. Attendees logged to Attendance.csv file.

![main](http://github.com/bmskarate/final_project_LHL/Readme_images/program_mainscreen.png)
![main](http://github.com/bmskarate/final_project_LHL/Readme_images/student_input_images.png)
![main](http://github.com/bmskarate/final_project_LHL/Readme_images/attendlog.png)


## Future Improvements
1. Add a feature to log when user leaves (break or clockout).
2. Add a feature to log when user returns (break or clockin).
3. Add face mask detection to ensure user has their mask on properly.
