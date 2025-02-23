# Sally-the-Line-Follower
The Line Follower Robot is an autonomous vehicle that follows a predefined path using IR sensors. It detects and follows a black line on white surface and adjusts its movements accordingly. This project is built using Arduino and is programmed using the Arduino IDE.

Working Principle:
-The IR sensors detect the line by distinguishing between black and white surfaces based on infrared reflectivity.
-The sensor data is sent to the Arduino Uno, which processes it and decides motor actions.
-The L298N motor driver receives signals from the Arduino and controls the speed and direction of the DC motors.
-The robot continuously adjusts its movement to stay on the line.

Challenges Faced:
-Sensor Calibration: Ensuring proper threshold values for different lighting conditions.
-Motor Speed Balancing: Adjusting PWM signals for smooth movement.
-Power Management: Optimizing battery usage for longer runtime.

Future Improvements:
-Implement PID control for smoother turns and precise line tracking.
-Add an ultrasonic sensor for obstacle detection.
-Upgrade to wireless control for remote monitoring
