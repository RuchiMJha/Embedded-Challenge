Embedded Challenge Fall 2024 Term Project  
“Embedded Sentry”  
Group 43    
Ruchi Jha 
Tanvi Takavane  
Neha Patil  

Motivation:  

In an age where security has become a center of focus for data storage, data access, and
robust protection of personal property, many different approaches to “hack-free” protection of
assets has emerged. These range from physical protection, to OTA, to biometrics. This
challenge focusses on designing an embedded system, using your dev boards, to provides a
mechanism to provide generic lock/unlock capabilities using your IMU (i.e. gesture control).  

Objective:  
● Use the data collected from a single accelerometer and/or gyro to record a hand
movement sequence as a means to generally “unlock” a resource.  
● Recorded sequence must be saved on the microcontroller, using a “Record Key” feature.  
● User then must replicate the key sequence within sufficient tolerances to unlock the
resource.  
● A successful unlock must be indicated by a visual indication, such as an LED or similar
indicator.  

Restrictions:  
● This is a group project to be done by groups of no more than 3 students  
● Only one microcontroller and one accelerometer/gyro may be used, specifically the one
integrated on your board.  
● You must use PlatformIO as we have done throughout the class  
● You will be allowed to use drivers/HAL functions available through the IDE  
● The accelerometer/gyro must be held in a closed fist of either hand while performing the
mechanical sequence.  
● An “enter key” and ”record” functionality must be developed to so the user knows when
to start the sequence of unlocking and recording respectively  
