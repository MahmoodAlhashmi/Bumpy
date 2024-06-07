Bumpy: A Two-Wheeled Self-Balancing Robot

Bumpy is a two-wheeled self-balancing robot. This project uses an Arduino Uno and various components to achieve self-balancing capabilities.
Components Needed

    1 Arduino Uno
    1 MPU6050 (Gyroscope and Accelerometer)
    2 MG995 Servos
    2 JGA25-370 DC Motors
    1 L298N Motor Driver

Schematic

Below is the schematic diagram for connecting the components:
Arduino Nano Connections

    servo_up_left (left servo) ---> Pin 3
    servo_up_right (right servo) ---> Pin 2
    enL (left motor enable) ---> Pin 11
    in1 (left motor input 1) ---> Pin 10
    in2 (left motor input 2) ---> Pin 9
    enR (right motor enable) ---> Pin 5
    in3 (right motor input 1) ---> Pin 8
    in4 (right motor input 2) ---> Pin 7
    MPU6050 SDA ---> A4
    MPU6050 SCL ---> A5
