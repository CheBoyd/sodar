# sodar


Laser & Ultrasonic Ranging Using Arduino and Processing
(Radar)



 



Surveillance device which
uses Arduino, laser sensor and Ultra Sonic Sensor to broadcast the information
to a monitor, using USB cable basically.
Thou the intended purpose is to broadcast to an android phone using Wi-Fi
module (ESP8266) for transmission through internet.



Safety and Security is always a big
concern, mostly in homes or work place, setting up a surveillance camera that
can monitor every inch and events all day long and having night vision mode
with tilt and pan option will cost a fortune and sometimes one would want to
monitor a place without compromising privacy. An economic device which does
almost the same but without any video surveillance footage features is what I
am focusing on.



The device senses objects that enters the proximity to be monitored using a laser light emitter with the help of photo resistor. Once the laser is cut a relay turns on Ultrasonic Sensor that rotate on a 180degree plane since the ultrasonic sensor is mounted over a servo motor, the servo motor rotates automatically to scan the area and sends data through the serial port to a computer. Then it displays the current angel of the servo motor and the distance between the Ultrasonic sensor and the object. The monitor display is coded in java using processing IDE. 





 



