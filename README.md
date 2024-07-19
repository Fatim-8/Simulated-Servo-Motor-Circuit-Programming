# Simulated-Servo-Motor-Circuit-Programming


## The goal is to demonstrate the ability to create an integrated electronic system containing multiple servo motors and programmatically control them.

To Do:

1. Using the "Tinkercad" simulation platform
   
   (https://www.tinkercad.com/dashboard)

2. Placing the necessary servo motor components in the Tinkercad workspace.
   
3. Wiring the servo motors correctly to the power sources and control terminals.

4.  Writing the programming code to control the movement and positioning of each servo motor within the simulation environment.
```
#include <Servo.h>

// Define variables
Servo servo1, servo2, servo3, servo4, servo5, servo6;
int servo1_pin = 2, servo2_pin = 3, servo3_pin = 4, servo4_pin = 5, servo5_pin = 6, servo6_pin = 7;

void setup() {
  // Attach the servo motors to their respective pins
  servo1.attach(servo1_pin);
  servo2.attach(servo2_pin);
  servo3.attach(servo3_pin);
  servo4.attach(servo4_pin);
  servo5.attach(servo5_pin);
  servo6.attach(servo6_pin);
}

void loop() {
  // Move the servo motors to their maximum position
  servo1.write(180);
  servo2.write(180);
  servo3.write(180);
  servo4.write(180);
  servo5.write(180);
  servo6.write(180);
  delay(1000); // Wait for 1 second

  // Move the servo motors to their minimum position
  servo1.write(0);
  servo2.write(0);
  servo3.write(0);
  servo4.write(0);
  servo5.write(0);
  servo6.write(0);
  delay(1000); // Wait for 1 second
}
```
5. Testing and verifying the functionality of the complete servo motor circuit.
   

https://github.com/user-attachments/assets/25737bc8-68fa-435e-94f0-b69b108e17d8

   
