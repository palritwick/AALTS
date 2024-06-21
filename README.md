# AALTS

**Accident Alert and Location Tracking System using TTGO TCALL and GPS - "AALTS"**

The systems will detect the occurrence of an accident, notify emergency services with the exact location of this collision and also inform a select number of emergency contacts that have been set by the user.
The Accident Alert and Location Tracking System is a valuable tool for improving road safety. By quickly detecting accidents and providing accurate location information to emergency services, the system can help to save lives and reduces injuries. The system’s combination of advanced sensors, micro-controller technology, GPS, and GSM makes it a versatile and reliable solution for enhancing road safety.

Working description : 

The TTGO TCALL module serves as the microcontroller and is responsible for establishing communuication and controlling the overall working of the system. When there is a sudden change in speed or angular velocity of the car which is detected by the MPU6050 motion and accelerometer sensor then an alarm is raised. If this happens for three consecutive time within a predefined time interval it indicates that an accident has taken place and the location(along with google map link) and speed is sent to an emergency contact which is already added in the system to notify about the happening. The location is detected by the NEO6M GPS module and also a voice call is sent to the registered number.

1. Real-time traffic monitoring and route optimization

2. Artificial intelligence (AI) for accident prediction

3. Vehicle-to-vehicle (V2V) communication

4. Integration with smart city infrastructure


 The Project demonstration: https://drive.google.com/drive/folders/1-36IUsbM22ReOtc-gKf3Y4SPivLfCrkb
