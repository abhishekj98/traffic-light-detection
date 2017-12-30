# traffic-light-detection
Real time traffic light detection using OpenCV and visual studio

Abstract:

The main idea of the project is to detect the traffic light for autonomous vehicles. We are detecting whether the traffic light is Red or Green and according to that it will display the output.  OpenCV and MATLAB environment used for our project. We eliminate some interferences with colours that are close to RED or GREEN, by reduce the brightness of the image. In the candidate recognition stage, we distinguish RED or GREEN, using the Cr component of the YCrCb colour space. We have eliminated some interferences in motion, such as car headlight, by compare the front and rear frames to see whether the tracking areas is intersected. We have used two functions with same code to detect RED and GREEN, further we can integrate them to shorten the length and the size of the code. We have used various concept of image processing like dilation, erosion, contours, convex hull, hierarchy of contours etc. for our project. At the end we have successfully got output of the code and our program is detecting the traffic light signal. 

