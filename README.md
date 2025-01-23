# DC-Motor-Control-using-Arduino-and-L293D-Motor-Driver
This project demonstrates how to control 4 DC motors connected to an Arduino UNO using the L293D motor driver. The motors perform specific movements based on the task requirements, including forward, backward, and alternating left and right.

---

## **Features**
- 🚀 **Forward Movement**: All motors move forward for 30 seconds.
- 🔄 **Backward Movement**: All motors move backward for 1 minute.
- ⬅️➡️ **Alternating Turns**: Motors alternate between right and left turns for 1 minute.
- 💡 **Flexible Design**: Modular code structure for easy expansion and maintenance.

---

## **Components Used**
1. 🖥️ **Arduino UNO**
2. ⚙️ **L293D Motor Driver (x2)**
3. 🛠️ **DC Motors (x4)**
4. 🔌 **Breadboard**
5. 🔗 **Connecting Wires**
6. 🔋 **9V Battery**

---

## **Circuit Diagram**
![Image](https://github.com/user-attachments/assets/eedf277e-03a1-4f63-81c4-dfaa82e9caed)

> **Note:** Ensure the motor driver connections match the Arduino pins as per the code. Power the motors using the external 9V battery.

---

## **Arduino Pin Connections**
| Motor       | Enable Pin | Input Pin 1 | Input Pin 2 |
|-------------|------------|-------------|-------------|
| Motor A     | 6          | 7           | 4           |
| Motor B     | 3          | 5           | 2           |
| Motor C     | 10         | 8           | 9           |
| Motor D     | 11         | 12          | 13          |

---

## **Code Overview**

The code consists of:

1. **Pin Definitions:**
   Each motor's enable and control pins are defined for clarity.

2. **Setup Function:**
   Initializes all motor pins as outputs and stops all motors initially.

3. **Loop Function:**
   Executes the following sequence:
   - Move forward for 30 seconds.
   - Move backward for 1 minute.
   - Alternate between right and left turns for 1 minute.

4. **Motor Control Functions:**
   - `moveForward()`
   - `moveBackward()`
   - `turnRight()`
   - `turnLeft()`
   - `stopMotors()`
   - `alternateRightLeft()`

---

## **How to Run**

1. 🛠️ **Set up the Circuit:**
   - Follow the circuit diagram and connect all components correctly.

2. 🖥️ **Upload the Code:**
   - Open the Arduino IDE.
   - Copy the code into a new sketch.
   - Upload the code to the Arduino UNO.

3. 🔋 **Power the Circuit:**
   - Ensure the Arduino is powered via USB or an external source.
   - Use the 9V battery to power the motors through the motor driver.

4. 🎥 **Observe the Movements:**
   - Motors will perform the forward, backward, and alternating turn movements as per the task requirements.

---

## **Future Improvements**
- ⚡ Add speed control for each motor using PWM signals.
- 🤖 Implement obstacle detection using sensors.
- 📡 Integrate Bluetooth or Wi-Fi for remote control.

---
