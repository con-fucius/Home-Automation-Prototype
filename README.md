# Home Automation System Prototype

This project demonstrates a home automation system prototype that integrates lighting control and climate regulation. The system uses claps to control lighting and a temperature sensor to automate fan operation based on the surrounding environment, offering a smart and interactive home experience.

---

## Features

1. **Lighting Control**:
   - Clap-based activation and deactivation of LED lights.

2. **Climate Regulation**:
   - Automatic fan control based on temperature readings from the DHT11 sensor.

3. **Prototype**:
   - Combines functionality into a simple and efficient design using readily available components.

---

## Components Used

### 1. **Arduino Mega Board**
   - **Input Voltage**: 7–12V (recommended), 6–20V (maximum range).
   - **Digital I/O Pins**: 54 (15 PWM outputs).
   - **Analog Inputs**: 16.
   - **Clock Speed**: 16 MHz.
   - **Connectivity**: USB connection, ICSP header, power jack.
   - **Additional**: Reset button.

### 2. **LEDs**
   - Polarity: Cathode (-ve), Anode (+ve).
   - Operating Current: 20mA.

### 3. **Motor Fan**
   - **Supply Voltage**: 5V.
   - **Current Consumption**: ~230mA.
   - **Controller**: Built-in L9110 motor controller.
   - **Dimensions**: 35mm x 27mm x 13mm.
   - **Fan Diameter**: 75mm.

### 4. **DHT11 Temperature and Humidity Sensor**
   - **Working Voltage**: 3.3V or 5V DC.
   - **Measurement Range**: 20–95% RH, 0–50°C.
   - **Resolution**: 8-bit (temperature & humidity).
   - **PCB Size**: 22mm x 20.5mm x 1.6mm.
   - **Interface**: 2.54 3-pin and 4-pin Grove compatible.

### 5. **Breadboard and Jumper Wires**
   - Essential for connecting components and creating the circuit.

---

## How It Works

1. **Lighting Control**:
   - A sound detection module detects claps.
   - LEDs are turned on or off based on the number of claps.

2. **Climate Control**:
   - The DHT11 sensor measures the ambient temperature.
   - When the temperature exceeds a threshold, the fan is automatically activated.

---

## Specifications

| **Component**        | **Specifications**                                    |
|-----------------------|------------------------------------------------------|
|   Arduino Mega        | 54 Digital I/O, 16 Analog Inputs, 16 MHz, 7–12V      |
|   LED                 | 20mA Operating Current                               |
|   Motor Fan           | 5V Supply, L9110 Controller, 75mm Diameter           |
|   DHT11 Sensor        | 0–50°C, 20–95% RH, 3.3V/5V DC                        |
|   Connecting Wires    | Jumper wires for prototyping                         |

---

## Setup and Usage

1. **Hardware Setup**:
   - Connect the DHT11 sensor, LEDs, and motor fan to the Arduino Mega via the breadboard using jumper wires.
   - Ensure proper polarity and voltage for all components.

2. **Software Setup**:
   - Program the Arduino Mega using the Arduino IDE.
   - Implement code to handle sound-based LED control and temperature-triggered fan operation.

3. **Operation**:
   - Use claps to control the LED lights.
   - Observe automatic fan activation when the temperature exceeds the set threshold.

---

## Applications

- Smart home systems.
- Prototypes for interactive and automated home environments.
- Educational projects for learning IoT and embedded systems.

---

## License

This project is open-source. Feel free to use, modify, and share for personal or educational purposes.
