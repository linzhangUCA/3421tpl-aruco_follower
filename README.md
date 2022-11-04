# ArUco Marker Follower
Guide your robot with an ArUco marker. Navigate the robot from the entrance of LSCA 105 to the blue marker next to the south wall of the classroom. 

## Requirement
Start your robot at the entrance of the classroom. Guide your robot with an ArUco marker to navigate to the designated area.
1. Define a new class to include two new functions: foward_left(), and foward_right().
2. Use built-in function in OpenCV to detect the ArUco marker.
3. Move your robot based on the location of the marker in your video images.


## Instructions: 
Complete `follow_aruco.py`
1. (20%) Retrieve video frames using RPi camera.
2. (30%) Detect and localize ArUco marker in every video frame.
3. (30%) Use appropriate navigation strategies (e.g. move "forward left" if marker shown on left half of the video frame; stop if robot cannot detect any marker).  
4. (20%) Upload a video to show the whole navigation process.

#### Note
- You can use any object to hold the ArUco marker.
- You may need to practice a little bit to better cooperate with your robot.
- A video streaming server can be useful for debugging.
- Remote control can be another useful debugging tool.
- You may want to tweek the motor speed to get a more comfortable driving experience. 

## Helpful Resources
- Waveshare Motor Driver Board [Wiki Page](https://www.waveshare.com/wiki/RPi_Motor_Driver_Board).
- [gpiozero example](https://gpiozero.readthedocs.io/en/stable/recipes.html#robot) of driving a robot.
- [API](https://gpiozero.readthedocs.io/en/stable/api_boards.html#robot) for Robot class in gpiozero. 
- [picamera2 example](https://github.com/raspberrypi/picamera2/blob/main/examples/mjpeg_server.py) for hosting live stream video.
- [picamera2 manual](https://datasheets.raspberrypi.com/camera/picamera2-manual.pdf)
