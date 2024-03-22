# Traffic Light Signal using IC 555

![Traffic Light](https://raw.githubusercontent.com/Azazel0203/traffic_light_ic555/main/image.png)

This project involves designing and building a model traffic light circuit using two 555 timer ICs along with various electronic components. The circuit emulates the behavior of traffic lights, with LEDs representing green, yellow, and red signals. The sequence of operation involves the green LED turning on for a specific duration, followed by a brief moment of the yellow LED, and then the red LED for a similar duration. This cyclic pattern repeats to simulate a traffic light system.

## Components Required

- 2 x 555 Timer ICs
- LEDs: 1 Red, 1 Yellow, 1 Green
- Resistors: 100K, 47K, 2 x 330R, 180R
- Capacitors: 2 x 100uF
- Breadboard
- Breadboard Connectors
- (5-12)V Power Supply

## Circuit Diagram

Refer to the provided circuit diagram for a detailed visualization of how the components are connected, including the 555 timer ICs, LEDs, resistors, and capacitors.

## Circuit Operation

The circuit utilizes two astable circuits, with the first one powering the second. Here's a breakdown of the operation:

- The first 555 timer IC's output state powers the second IC.
- The red LED is designed to turn on only when the first 555 timer IC's output is at 0V. This is achieved by its connection to a positive voltage source.
- The yellow LED turns on during the discharge mode of the second 555 timer IC.
- The green LED is activated when the output of the second 555 timer IC is at a positive voltage.
- The circuit starts with the green LED on due to the initial state of the first 555 timer IC's output.
- The second 555 timer IC's capacitor charges until its output turns off, causing the yellow LED to light up.
- The first 555 timer IC's capacitor charge triggers a transition, turning off the yellow LED and turning on the red LED.
- This cycle repeats, creating a simulation of traffic light behavior.

## Conclusion

In conclusion, this project showcases a model traffic light system using 555 timer ICs. The circuit effectively replicates the sequential operation of traffic lights by utilizing two 555 timer ICs to control LED timings. It provides a practical and educational demonstration of the 555 timer IC's capabilities in designing traffic light systems.
