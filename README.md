# Driver-Drowsiness-Detection

The proposed solution has 4 major aspects.

•	Drunk driver detection System
•	Road Speed Alert System
•	Driver Drowsiness and Distraction Detection
•	Misbehaviour Detection.
Camera Such as Wifi camera can be boarded on the dashboard to monitor, the activity of Driver. With the use of Wifi camera, the prediction and analysis needs to take place on cloud server. 

Another Solution is to have a On Board device ex. Raspberry Pi to predict results with lower latency. 

Drunk driver detection System
Drunk driver can be detected using redness of eye, positioning of pupil , closing of the eyes and behaviour changes committed by driver like distraction while driving. 
Road Speed Alert System
We can use Mobile GPS that takes the current location that the driver is driving in and retrieves the speed limit for that road from the Maps Api Service which triggers a voice alarm to notify the driver of overspeeding if the uSpeed is greater than the specified speed limit for the road. 

Driver Drowsiness and Distraction Detection
The driver drowsiness system uses a HOG based image detection algorithm to detect 68 points on a face. 
The system uses a pre-trained dataset shape_predictor_68_face_landmarks.dat file.
Successfully taken care conditions under bright light conditions: 
1.Yawning 
2.Closed eyes 
3.Both Yawn and Closed eyes 
4.Non frontal face detection 
5. Face detection within specified boundary region




Pictures shows the demo of the detection system
    



USING Wifi Inbuilt Camera on Car Dashboard
With the use of Wifi camera, the prediction and analysis needs to take place on cloud server. 

One device that acts as a dashcam and a GPS device at the same time along with a cloud storage.

Detection algorithm can be deployed on the Wifi Cam and prediction and analysis could be seen on cloud server. There is latency involved and there can be loss of control due to technicality involved.




Powering up Raspberry Pi 
We can use Micro USB for giving power supply to Raspberry Pi. The MicroUPS can be charged from the car itself using car power supply though USB.
Specifications for the UPS :
•	5V UPS with upto 12 hours power backup to be used with devices with MicroUPS input (5V) 
•	Micro USB B type input, USB A type output 
•	5V up to 2A 10W uninterrupted output
•	5000mAh BIS Certified Lithium Ion battery with over voltage, under voltage and over current protection.


Camera For Raspberry Pi along with GPS Module.
We can use Camera Module with 222 Fov FishEyes Wide Angle 5 MP Webcam 1080p Sensor for Raspberry Pi 4.
•	The Camera Module Specifications is 2592 x 1944 Pixel Static Images, 1080 p @ 30 fps, 720 p @ 60 fps and 640 x480 p 60/90 Video Recording,5 Megapixel sensor OV5647
•	It has CSI Interface carries pixel data from the camera back to the processor.

GY-NEO6V2 NEO-6M V2 GPS Module with Antenna and EPROM for location.

•	GY-NEO6V2 or NEO-6 is a product of U-Blox and comes in a series of stand-alone GPS receivers with the feature of the high-performance 6-position engine. 
•	It uses the latest technology of U-Blox and gives precise positioning. It has onboard battery and memory that makes is perfect for battery operated devices. 
•	The module is compatible with any microcontroller and Arduino and comes with external Antenna.
I have attached some reference links for the same .


https://www.amazon.com/dp/B07T9ZCQLW/ref=sspa_dk_detail_5?psc=1&pd_rd_i=B07T9ZCQLW&pd_rd_w=LBSZS&pf_rd_p=7d37a48b-2b1a-4373-8c1a-bdcc5da66be9&pd_rd_wg=znsyX&pf_rd_r=CXX0Q61MRXEJQ4M0FYHD&pd_rd_r=71548cd9-a310-4ce0-8a23-5a438ad0f460&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyT0xPT1JZRkQxSEcmZW5jcnlwdGVkSWQ9QTAyNzc1NjUzVDFVVVQ0Nk5NNkxKJmVuY3J5cHRlZEFkSWQ9QTA0NjY5MjQxV09HVjQwTjdYNlNJJndpZGdldE5hbWU9c3BfZGV0YWlsJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==


https://www.amazon.in/MicroUPS-RegalDream-Technologies-Hours-Backup/dp/B07YQ8C5PC/ref=sr_1_1?adgrpid=67698879571&dchild=1&ext_vrnc=hi&gclid=CjwKCAjwrKr8BRB_EiwA7eFapqMjWbUmZbB8ufBF8Mg3875NlqXW9UfLtiuYe4VFuwfsugaJU8JzPxoC1ZcQAvD_BwE&hvadid=398027785845&hvdev=c&hvlocphy=9300728&hvnetw=g&hvqmt=b&hvrand=2385458555229795189&hvtargid=kwd-

738456761912&hydadcr=26420_2176909&keywords=5v+2a+ups&qid=1602921619&sr=8-1&tag=googinhydr1-21

https://www.amazon.com/THINKWARE-Dashboard-Recorder-G-Sensor-Recording/dp/B07RLPWZX3/ref=sr_1_10?dchild=1&keywords=camera+for+dashboard&qid=1602921668&sr=8-10

