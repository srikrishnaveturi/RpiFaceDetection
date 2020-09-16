# RpiFaceDetection
accessing the video from the PiCam onto my computer and then sending(through sockets) back instructions for the led,this could've been done solely on the rpi. but for future projects like a neural network car, this process would be very helpful as the rpi cannot process huge neural nets,but my laptop can

using the dlib frontal face detector on the server(computer) and getting the live stream from the pi, we can process if there is a face in the frame or not and then we send back a string to the pi.
finally, according to the string, we can control the LED with the pi.
