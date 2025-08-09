# Human Following Robot
In this repository, there are links, code, circuit diagram and procedure to help you design and develop a human-following robot using Arduino Uno, Ultrasonic, and Infrared sensors.

## Acknowledgement
This project was developed with valuable guidance and references from multiple sources. I would like to express my sincere gratitude to DIY Builder, whose tutorials guided me throughout the process.

📺 Channel: (https://www.youtube.com/@DIYBuilder)
🎥 Video: (https://www.youtube.com/watch?v=yAV5aZ0unag)

I would also like to extend my heartfelt thanks to ComedKares Innovation Hub for their mentorship and support. Whenever I encountered challenges, they not only helped me resolve the issues but also took the time to explain the underlying concepts, enabling me to gain a deeper understanding. Their guidance played a crucial role in the successful completion of this project.

🌐 Website: (https://www.comedkares.org)

## Introduction
This project involves the development of a human-following robot capable of autonomously tracking and maintaining a safe distance from individuals. The robot utilizes infrared (IR) sensors to detect and follow the heat signatures emitted by humans, ensuring reliable tracking in various environments. In addition, an ultrasonic sensor is integrated to measure proximity and prevent collisions, allowing the robot to maintain an appropriate distance from the person it follows.

The system is powered by an Arduino UNO microcontroller, which processes sensor data and controls the robot’s movements. This combination of sensors and microcontroller enables the robot to operate effectively, making it suitable for applications such as personal assistance, automated luggage carriers, and service robots in public spaces.

## Requirements
I purchased all my components from Robocraze. It is a trusted online eCommerce for projects such as these. They also provide components at a reasonable price as compared to it's competitors. As such, I will name the components, as well as leave a link.
- Arduino UNO (https://robocraze.com/products/uno-r3-board-compatible-with-arduino)
- L293D Motor Driver Shield (https://robocraze.com/products/l293d-motor-driver-shield-for-arduino)
- Ultrasonic Sensor (https://robocraze.com/products/hc-sr-04-ultrasonic-sensor)
- Infrared Sensor (https://robocraze.com/products/ir-proximity-sensor-1)
- Servo Motor (https://robocraze.com/products/sg90-micro-servo-motor)
- BO Motors
- Wheels
- Chassis (https://robocraze.com/products/2wd-2-wheel-smart-diy-robot-car-chassis-kit)
  (The link provided for Chassis is a kit containing BO Motor as well as wheels. And thus, I have not provided link for Wheels and BO Motors.)
- 18650 Batteries (https://robocraze.com/products/3-7v-1200mah-18650-battery)
- Battery Holder (https://robocraze.com/products/18650-dual-battery-holder-with-cover-and-on-off-switch)
- Jumper Wires (https://robocraze.com/products/jumper-wire-set-m2m-m2f-f2f-40-pcs-each)
- Type A to B Cable: (https://robocraze.com/products/usb-a-b-cable-3-0-cm)
  (This cable is required to upload the code from your laptop/PC to Arduino UNO microcontroller.)
- Arduino IDE (https://www.arduino.cc/en/software/)
  (You will need an IDE to upload the code to Arduino microcontroller. So, I have given the link to download it here.)

## Procedure
### Step 1: Procure the Components
- Using the link given above, or by other means, procure the components required for this project.

### Step 2: Solder the Motors
- If you have bought a new motor, they most probably won't be soldered. So, have it soldered.
- (It is better if you can color code the motors, as it will be easier to connect. Eg, Red for forward motion, and black for backward motion)

### Step 3: Attach Motors to Chassis
- Stick the Motors to the chassis, followed by which attach the wheels.

### Step 4: Upload the Code to Arduino UNO
- Open Arduino IDE, and paste the code. The code is provided in this repository as code.ino.
- Connect the Arduino UNO to your Laptop.
- Select Port and choose the available Port (Eg. COM3)
- Select Board and select Arduino UNO (If you cannot see any boards, go to Boards Manager and Install Arduino Boards.)
- Next, click on Verify (Optional)
- Click on Upload.

### Step 5: Mount the Arduino
- Mount the Arduino UNO on top of the chassis

### Step 6: Mount the Driver Shield
- Mount the L293D Motor Driver Shield on top of Arduino.
- Next, connect each of the motor's wires to the motor slot available in the shield.

### Step 7: Mount the Batteries
- Attach the Batteries to the chassis.
- (Make sure the switch is off if there is one, or don't fully connect the batteries until the circuit connection is complete.)

### Step 8: Attach the Sensors and Servo Motor
- By referring to the Circuit Diagram, or the Youtube Tutorial, complete the circuit Connection.

### Step 9: Check the Circuit Connections
- You can never be too careful. Cross verify the circuit diagram and connections, and make sure all of them are connected properly, and no wires are loosely connected.
- Be extra careful while handling the batteries, they are fragile.
- Also, L293D Motor Driver Shields are sensitive and may spoil if there are huge spikes in Voltage provided to it.
