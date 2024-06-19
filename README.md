# ZECA
Zero-configuration Alarms: Towards Reducing Distracting Smartphone Interactions while Driving

The rising ubiquity of smartphones for navigation, driver mode, etc., has increased their use significantly among drivers; however,
there are growing numbers of road fatalities being reported due to distractions from the phone while driving. In contrast to the existing
solutions that use a camera or other communication media on the car or need external setups, this paper proposes a solution called
ZeCA, where the smartphone itself can identify in real-time with zero pre-configurations whether its user is driving while engaging in
a high-distraction interaction with the phone. ZeCA runs as a smartphone background service and generates audio-visual alerts when
the phone can distract the driver. A thorough evaluation and usability study of ZeCA with 50 different models of vehicles driven by 70
drivers over 5 countries indicates that the proposed solution can infer distracting smartphone interactions with > 80% accuracy and a
70% reduction in smartphone usage during drivingWe have collected the data of driver while he is driving utilising the mobile phone. This project tries to blindly detect whether the smartphone is in the hands of the driver or passenger. Further, it also generates an alert whenever a driver is engaged in some fatal activities with the mobile phone. 

## Dataset
We have collecetd the data for 70 drivers. This dataset comprises of Audio, IMU, Proximity and Screen(On/Off) of the smartphone that is being utilised by the driver. This dataset also contains the Video clips of 1 minute each as a front view and back view using the NEXAR camera. The front view captures the drivers' action while driving and the rear view captures the road scenes appearing from the windscreen of the car. Here, we collect the data from the application and sends it to backend for processing and estimation. The backend after estimation generates an alert for the user after an interval of 1 minute.
