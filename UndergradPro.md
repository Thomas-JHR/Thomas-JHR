### A sensor framework for balanced posture and gait study ####
****Purpose:****

  - model the client posture in the application platform called Unity by building a constructive algorithm in Visual Studio, followed by producing a smartly sensory system on the device in order to help the client to relieve the pain from the posture adjustment

  - help the developers to seek a balanced position with the horizontal center and center of gravity in the designed platform

****Methods:****
  - Both the raw data received from the Kinect sensor and initially deifned image from the Unity platform are uploaded  
<p align="center">
 <img src=https://github.com/Thomas-JHR/Thomas-JHR/blob/main/Undergrad2.JPG width=85% height=85%>
</p>

  - ****A Kinect sensor**** is used to detect whether the body structure is horizontal or not once the original data is uploaded. The received data can be adjusted until the maxima difference among each horizontal point with using coding algorithms is below threshold values.

  - ****Accelerometers**** on the shoulder and hands are required to tell whether or not the client’s data is symmetrical. The coding algorithms help the users to adjust the symmetric difference of their bodies by measuring instant acceleration on each direction.

  - ****Forcing sensors**** show the pressure data under the feet. The coding algorithms locate the sensors with unequal data point until the body structure is balanced. 

<p align="center">
 <img src=https://github.com/Thomas-JHR/Thomas-JHR/blob/main/Undergrad1.JPG width=85% height=85%>
</p> 

****Results:****

  - The team used the Kinect sensor to find the horizontal symmetry, and used the Arduino IDE to identify the center of gravity. The Unity programming platform is acted as a user interface to show three-dimensional image data and data interpretation.
  - 
<p align="center">
 <img src=https://github.com/Thomas-JHR/Thomas-JHR/blob/main/Simulation_Clip.JPG width=85% height=85%>
</p> 

  - Please feel free to download and watch simulation videos
    -  [Symmetric simulation](https://github.com/Thomas-JHR/Thomas-JHR/blob/main/Body%20symmetric.mp4)
    -  [Balance simulation](https://github.com/Thomas-JHR/Thomas-JHR/blob/main/Balance.mp4)
   

