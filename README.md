
# Build Instructions For MQ3 SENSOR


### Introduction
The project aims to reduce accidents caused my impared driving.My sensor MQ3 provides analog resistive output based on Alcohol Concentration.The project was selected and the proposal was introduced.
MQ3 sensor or alcohol sensor is suitable for detecting alcohol concentration on breath, just like common breathalyzer
.It has a high sensitivity and fast response time. Sensor provides an analog resistive output based on alcohol concentration. 
This Sensor will be used with the app known as Breathalyzer which is made for personal use for self control or general health issues
<img src="https://github.com/MohitaPrabhakar/Mq3Sensor/blob/master/Capture.PNG" alt="">

### Budget 
The stuff required for creating the Breathalyzer can be seen below with the cost, which can be ordered from Amazon ,Sparkfun or Ebay.You may not be able to buy MQ3 SENSOR individually ,so you can order a set of MQx sensors which wouldnt cost more than $20 on amazon . 

<img src="https://github.com/MohitaPrabhakar/Mq3Sensor/blob/master/Picture1.png"  alt="">

### Time Commitment
After selecting the project,make a schedule and act accordingly.It didnt take me much time to complete the project,because I was doing everything before time.If you dedicate 2-3 hours every week for the project ,you will be able to manage to finish the project on time.
After receiving the order,installing necessary stuff on the raspberry pi,it took 3-5 hours to set up the hardware,write a code and test the project.

### Setting up Raspberry Pi 
After receiving the order, the first step is installing Raspian on Raspberry Pi.These are the steps for installation as given below:-

#### Step 1: Download Raspbian
It can easily take more than half an hour to download the software.Download Noobs from https://www.raspberrypi.org/downloads/ 

#### Step 2: Unzip the file
The Raspbian disc image is compressed, so you’ll need to unzip it. The file uses the ZIP64 format, so depending on how current your built-in utilities are, you need to use certain programs to unzip it.

#### Step 3: Write the disc image to your microSD card
Select the drive of your SD card in the ‘Device’ dropdown.

#### Step 4: Put the microSD card in your Pi and boot up
Select ‘Write’ and wait for the process to finish which may take around 20 minutes to complete.
 
 
 ### Writing the Script for the MQ3 sensor
 Here is the python Script I used to test my alcohol gas sensor. <br>
<img src="https://github.com/MohitaPrabhakar/Mq3Sensor/blob/master/python.PNG"  alt=""> <br>
<br>
Th Raspberry pi is connected with the Mq3 sensor in such a way that VCC,Dout,Aout of the MQ3 Sensor is connected to the pin Vcc(4),Ground(6) and GPIO14(8) respectively as given below in the picture.
<br>
After the connections are made ,the python script is made to run.
<br>
<img src="https://github.com/MohitaPrabhakar/Mq3Sensor/blob/master/sensorconnection.PNG"><br>



### Unit Testing


### Production Testing
