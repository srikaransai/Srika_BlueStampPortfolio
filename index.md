# Gesture controlled robot
I built a gesture-controlled robot that moves forward, backward, left, and right based on the movement of my hand. The biggest challenge was connecting the motion sensor, Bluetooth modules, motors, and Arduino boards so they could communicate reliably. Completing the robot taught me how hardware and code work together, and it was rewarding to see the robot respond correctly to my gestures.



| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Srikaran S | Eastside preperatory school | Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone


<iframe width="320" height="576" src="https://www.youtube.com/embed/3eiIRPdu9g4" title="Srikaran S. Milestone 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my final milestone, I successfully completed a gesture-controlled robot that can move forward, backward, left, and right based on the movements of my hand. Since my previous milestone, I finished connecting and programming the two Bluetooth modules, tested all four motors, and used the accelerometer in the hand controller to detect different gestures. I also improved the code so that the robot responds more consistently and does not repeatedly send commands when my hand remains in the same position.

One of my biggest challenges at BSE was getting the Bluetooth modules to communicate correctly. At first, the modules would not enter AT mode or send data properly, so I had to carefully check the wiring, baud rates, and code. Another challenge was adjusting the accelerometer thresholds so that the robot would recognize intentional gestures without moving accidentally. My biggest triumph was seeing the robot move for the first time using only my hand movements. It was rewarding because it showed that the mechanical, electrical, and programming parts of the project were finally working together.

Throughout this project, I learned about Arduino programming, Bluetooth communication, accelerometers, motor drivers, circuits, debugging, and the engineering design process. I also learned that building a working prototype requires patience and repeated testing. When something did not work, I had to isolate the problem, test each component individually, and make changes based on the results.

In the future, I hope to learn more about robotics, electrical engineering, and wireless communication. I would like to improve the robot by making its movements smoother, increasing its range, and designing a smaller and more comfortable hand controller. I am also interested in adding more advanced features, such as speed control, obstacle detection, or machine learning that could recognize more complex gestures. Everything I learned at BSE has given me a stronger foundation for creating more advanced engineering projects in the future.



# Second Milestone



<iframe width="320" height="576" src="https://www.youtube.com/embed/HNJWbqaMJu0" title="Srikaran S. Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


 At this time i have successfully connected both of the Bluetooth modules. What has really surprised me through the process of completing this project so far is the amount of attention you have to give to the wiring as it is a concept that i struggled to learn. It took around 2-3 days just for me to understand and connect the two modules. Before my final milestone, I want to be able to get the car moving from the hand module and move on to modifications. 


# First Milestone

<iframe width="873" height="505" src="https://www.youtube.com/embed/j5-xCwY42b8" title="Srikaran S. Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

 Right now i have completed my first milestone which was to complete the car chassis. The car chassis consists of 4 motors, a motor driver, two metal plates, a battery pack, 4 wheels, and an Arduino Uno. Basically the Ariduno will send the code to the motor driver which then will execute the 4 motors to work properly. Right now, with my car chassis completed, I started testing all the motors to see if they work. They all worked perfectly! Some challenges I face right now are definatly the bluetooth side of things. It is very difficult for me to understand right now, so i have to learn a lot. Moving forward, my focus is now on the blutooth module which will probably be the hardest part of the entire project, but I am excited to learn more about it.

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials


| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Car Chassis Kit | Provides the frame, wheels, and motors for building the robotic car. Quantity: 1 | $39.99 | <a href="https://www.amazon.com/dp/B0DJ7BT1V5/"> Link </a> |
| Screwdriver Kit | Used to assemble, tighten, and remove screws on the robot. Quantity: 1 | $5.94 | <a href="https://www.amazon.com/Small-Screwdriver-Set-Mini-Magnetic/dp/B08RYXKJW9/"> Link </a> |
| Arduino Uno Clone | Controls the robot's motors, sensors, and other electronic components. Quantity: 1 | $14.98 | <a href="https://www.amazon.com/ELEGOO-Board-ATmega328P-ATMEGA16U2-Compliant/dp/B01EWOE0UU/"> Link </a> |
| Electronics Kit | Contains jumper wires, resistors, LEDs, buttons, and other prototyping components. Quantity: 1 | $14.00 | <a href="https://www.amazon.com/Smraza-Electronics-Potentiometer-tie-Points-Breadboard/dp/B0B62RL725/"> Link </a> |
| Breadboard Kit | Allows electronic circuits to be built and tested without soldering. Quantity: 1 | $8.79 | <a href="https://www.amazon.com/Breadboards-Solderless-Breadboard-Distribution-Connecting/dp/B07DL13RZH/"> Link </a> |
| Arduino Nano 33 BLE Sense | A compact microcontroller with Bluetooth and built-in sensors for wireless control and data collection. Quantity: 1 | $39.70 | <a href="https://www.amazon.com/Arduino-Nano-Sense-headers-ABX00070/dp/B0BQHZ88WD/"> Link </a> |
| Micro USB Cable | Connects compatible Arduino boards to a computer for programming and power. Quantity: 1 | $5.00 | <a href="https://www.amazon.com/Charging-Transfer-Android-Trustable-MYFON/dp/B098DW7485/"> Link </a> |
| Accelerometer | Measures the robot's acceleration, movement, tilt, and impacts. Quantity: 1 | $9.00 | <a href="https://www.amazon.com/dp/B0D2TJVMNY/"> Link </a> |
| HC-05 Bluetooth Module | Allows the robot to communicate wirelessly with another Bluetooth device. Quantity: 2 | $9.00 | <a href="https://www.amazon.com/DSD-TECH-HC-05-Pass-through-Communication/dp/B01G9KSAF6/"> Link </a> |
| Breadboard Power Supply | Supplies regulated power to components connected to the breadboard. Quantity: 1 | $8.00 | <a href="https://www.amazon.com/ALAMSCN-Solderless-Breadboard-Battery-Arduino/dp/B08JYPMCZY/"> Link </a> |
| 9V Batteries | Provide portable electrical power for testing or operating the circuit. Quantity: 1 pack | $8.69 | <a href="https://www.amazon.com/Amazon-Basics-Performance-All-Purpose-Batteries/dp/B00MH4QM1S/"> Link </a> |
| Velcro Tape | Secures electronic components, batteries, and wires to the chassis. Quantity: 1 | $8.00 | <a href="https://www.amazon.com/Art3d-Sticky-Double-Sided-Command-Adhesive/dp/B0B58FGF8H/"> Link </a> |
| Digital Multimeter (DMM) | Measures voltage, current, resistance, and checks electrical connections. Quantity: 1 | $9.99 | <a href="https://www.amazon.com/dp/B0CXM242J1/"> Link </a> |

