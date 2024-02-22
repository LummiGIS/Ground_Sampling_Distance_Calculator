# Ground_Sampling_Distance_Calculator
GSD Calculator for different drone cameras


Given the camera CMOS sensor size in mm, the focal lenght of the camera in mm, the size of the resulting images in pixels, and the height above ground in meters this script will calculate the spatial resolution (or ground sampling distance) in centimeters, and the image footprint.  This tool assumes a flat ground plane and a nadir facing camera.  

Some cameras CMOS do not uses pixels on the edge.  CMOS values may be an over-estimation of the sensor size.  The values returned from this script will be a best case senerio.
