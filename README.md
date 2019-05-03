# Remote Control Transmitter
This repository holds the source code for my multifunctional radio controller. The NRF24L01 transeiver module is responsible for the radio communtication of the controller. It features 14 channels, 6 of which are analog inputs and 8 digital inputs.

**Transmitter Inputs**  
\- Joysticks (x2)  
\- Potentiometers (x2)  
\- Toggle switches (x2)  
\- Tactile buttons (x6)  
\- IMU MPU6050 Accelerometer and Gyroscope (x1)

### Circuit Diagram  
*Add Later*

### PCB Design   
*Add Later*

## Subdirectories
* **transmitter\_code:**  
  For wireless communication, the [SPI](https://www.arduino.cc/en/reference/SPI) and [RF24](https://github.com/nRF24/RF24) libraries are used. The [I2C](https://www.arduino.cc/en/reference/wire) libary is used for the accelerometer module.
  
  

## Acknowledgments
* Vincent Driessen's '[Git Branching Model](https://nvie.com/posts/a-successful-git-branching-model/)'
