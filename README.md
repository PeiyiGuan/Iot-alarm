# What is IoT-alarm
IoT-alarm is an internet of things application runs on rasberry pi,an motion sensor was connected to the pi, the pi will send signal to ifttt server once it is triggered. IFTTT server is local server written in java.

# How to run it

## Start the server
Compile the IFTTT server: 
```javac IFTTTServer.java```
Then start the server:
```java IFTTTServer 8080```

## Start the alarm in pi

Compile the application with ```makr``` command.
then Run the application :
```./tester```

# What was learned
* Use of wiringPi lib
* Understanding and implementation of IFTTT server
* Communication between the application running on Pi and the IFTTT server.

# License

MIT(https://choosealicense.com/licenses/mit/)




