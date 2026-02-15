# Phase 1: Phase 1: Foundations and Basic Motor Control

⏱️ **Estimated Duration:** 1 week

---

## 🎯 Milestone 1: Arduino Setup & Basic Output

### Task 1: Install Arduino IDE and Drivers

- [ ] **Status:** Not Started

**Description:**
Set up the Arduino Integrated Development Environment on your computer and install necessary drivers for the Arduino Nano.

**✅ Definition of Done:**
> The Arduino IDE is successfully installed, and the computer recognizes the Arduino Nano board when connected via USB.

**Concepts:** `Arduino IDE` `Drivers` `Development Environment`

**📚 Resources:**
- 🎥 [Installing Arduino 2 for Arduino Nano - YouTube](https://www.youtube.com/watch?v=fkBL77MNnUQ)
- 🎥 [Arduino Nano | CH34X Driver Install | Fix driver issues - YouTube](https://www.youtube.com/watch?v=kr1sm-d31FU)
- 🎥 [Quick guide how to install driver for arduino boards UNO/MEGA/NANO](https://www.youtube.com/watch?v=mDrV8b1E6zI)
- 📖 [Arduino nano and Windows 11](https://forum.arduino.cc/t/arduino-nano-and-windows-11/1278435)
- 📖 [Arduino Nano V3.0 - avrdude Upload Failure - Core Electronics Forum](https://forum.core-electronics.com.au/t/arduino-nano-v3-0-avrdude-upload-failure/18214)
- 📖 [Having trouble connecting to a CH340 USB Arduino Board - Jetson ...](https://forums.developer.nvidia.com/t/having-trouble-connecting-to-a-ch340-usb-arduino-board/112061)
- 📖 [Computer cannot find the Arduino Nano 33 IoT](https://forum.arduino.cc/t/computer-cannot-find-the-arduino-nano-33-iot/620505)
- 📖 [Nano every missing drivers - Page 2 - Arduino Forum](https://forum.arduino.cc/t/nano-every-missing-drivers/598252?page=2)

---

### Task 2: Blink an LED

- [ ] **Status:** Not Started

**Description:**
Write and upload a simple program to make the onboard LED (or an external LED) on the Arduino Nano blink at a regular interval.

**✅ Definition of Done:**
> An LED connected to the Arduino Nano blinks consistently at a user-defined interval after code upload.

**Concepts:** `Digital I/O` `Basic Programming` `LED`

**📚 Resources:**
- 🎥 [How to Blink an LED with an Arduino Nano - YouTube](https://www.youtube.com/watch?v=dRAAIrpI1hg)
- 🎥 [How to led blink with Arduino nano - YouTube](https://www.youtube.com/watch?v=Rbdl2Ii10b0)
- 🎥 [How to Blink an LED with Arduino (Lesson #2) - YouTube](https://www.youtube.com/watch?v=FKekzzj5844)
- 🔗 [Programming the Arduino Nano | jessevdk - GNOME Blogs](https://blogs.gnome.org/jessevdk/2012/11/20/programming-the-arduino-nano/)
- 🎥 [BLINKING LED ON BREADBOARD - Arduino tutorial #2 - YouTube](https://www.youtube.com/watch?v=Smfzx4WBb9o)
- 🔗 [Multitasking (blinking and testing if statements) - Arduino Forum](https://forum.arduino.cc/t/multitasking-blinking-and-testing-if-statements/1192970)
- 🔗 [How do I control the onboard LEDs of my Arduino Nano 33 BLE ...](https://arduino.stackexchange.com/questions/80323/how-do-i-control-the-onboard-leds-of-my-arduino-nano-33-ble-sense)

---

### Task 3: Establish Serial Communication

- [ ] **Status:** Not Started

**Description:**
Write a program to send messages from the Arduino to the computer's Serial Monitor. This is crucial for debugging.

**✅ Definition of Done:**
> The Arduino Nano successfully sends custom text messages that are visible in the Arduino IDE's Serial Monitor.

**Concepts:** `Serial Communication` `Debugging` `Data Output`

**📚 Resources:**
- 🎥 [How to Use the Arduino Serial Monitor - YouTube](https://www.youtube.com/watch?v=j2qrRxQ9mSs)
- 🎥 [Serial Communication between Raspberry Pi and Arduino [1H ...](https://www.youtube.com/watch?v=jU_b8WBTUew)
- 💻 [Keepalive timeout for default MQTT Broker is 10s, pubsubclient is ...](https://github.com/knolleary/pubsubclient/issues/239)
- 🎥 [PLC vs Industrial Open-Source Controller (Arduino-Compatible ...](https://www.automationdirect.com/videos/video?videoToPlay=KOjPn9LVcjI)
- 🔗 [Is is possible to simultaneously use Arduino serial monitor while ...](https://stackoverflow.com/questions/15918058/is-is-possible-to-simultaneously-use-arduino-serial-monitor-while-receiving-data)
- 🔗 [Separate serial monitor from sending serial data. - Arduino Forum](https://forum.arduino.cc/t/separate-serial-monitor-from-sending-serial-data/562054)
- 🔗 [using the serial port to send data from python to Arduino - how to do?!](https://forum.arduino.cc/t/using-the-serial-port-to-send-data-from-python-to-arduino-how-to-do/614802)

---

## 🎯 Milestone 2: Motor Driver & Single Motor Control

### Task 1: Wire L298N Motor Driver with a DC Motor

- [ ] **Status:** Not Started

**Description:**
Connect a single DC motor to the L298N motor driver module and the motor driver to the Arduino Nano.

**✅ Definition of Done:**
> One DC motor is correctly wired to the L298N motor driver, and the motor driver is connected to the Arduino Nano's digital pins for control, along with a suitable power source for the L298N.

**🤔 Decision Point:**
> How will you power the L298N Motor Driver and, consequently, the DC motors?

Options:
- **Arduino 5V Pin**: Use the 5V output from the Arduino Nano to power the L298N. This is simple but risky for power-hungry motors.
- **Separate 9V Battery (or external power supply)**: Provide a dedicated 9V battery or external power supply to the L298N motor driver. This is recommended for robust motor control.

**Concepts:** `Motor Driver` `DC Motor` `Wiring` `H-Bridge`

**📚 Resources:**
- 🔗 [Controlling DC Motors with the L298N Dual H-Bridge and an Arduino](https://dronebotworkshop.com/dc-motors-l298n-h-bridge/)
- 🎥 [How to use the L298N Motor Driver with Arduino - Quick Tutorial](https://www.youtube.com/watch?v=E2sTbpFsvXI)
- 🎥 [How to use L298N with Arduino (with code) - YouTube](https://www.youtube.com/watch?v=wjFW-TNq8Og)
- 🔗 [How to wire l298n motor driver - General Guidance - Arduino Forum](https://forum.arduino.cc/t/how-to-wire-l298n-motor-driver/404543)
- 🔗 [Code help for running DC motor (Arduino Nano) - General Guidance](https://forum.arduino.cc/t/code-help-for-running-dc-motor-arduino-nano/703127)
- 🔗 [Motor driver sketch and code - Arduino Forum](https://forum.arduino.cc/t/motor-driver-sketch-and-code/465814)

---

### Task 2: Implement Single DC Motor Control (Forward/Backward/Stop)

- [ ] **Status:** Not Started

**Description:**
Write Arduino code to control a single DC motor connected via the L298N motor driver. The motor should be able to spin forward, backward, and stop.

**✅ Definition of Done:**
> The DC motor can be programmatically started to spin forward, stopped, and then started to spin backward using Arduino code, with control over the duration of each state.

**Concepts:** `Motor Control` `Digital Write` `Motor Driver Library`

**📚 Resources:**
- 🔗 [Controlling DC Motors with the L298N Dual H-Bridge and an Arduino](https://dronebotworkshop.com/dc-motors-l298n-h-bridge/)
- 🔗 [How to control a DC motor with the Arduino Uno and the L298N Dual Motor Controller](https://mschoeffler.com/2017/04/02/how-to-control-a-dc-motor-with-the-arduino-uno-and-the-l298n-dual-motor-controller/)
- 🎥 [Controlling DC Motors with the L298N H Bridge and Arduino](https://www.youtube.com/watch?v=dyjo_ggEtVU)
- 💻 [AndreaLombardo/L298N: An easy to use Arduino library to ... - GitHub](https://github.com/AndreaLombardo/L298N)
- 💻 [L298N Motor Driver Interfacing with Arduino - GitHub](https://github.com/YogeshwaranP-05/Arduino-L298N-Motor-Driver)
- 🔗 [MicroPython: ESP32/ESP8266 DC Motor (L298N Driver](https://randomnerdtutorials.com/micropython-esp32-esp8266-dc-motor-l298n/)
- 🔗 [I am wondering if I really need PWM and I2C for this project](https://forum.arduino.cc/t/i-am-wondering-if-i-really-need-pwm-and-i2c-for-this-project/687417)
- 🎥 [Driving DC Motors with Microcontrollers - YouTube](https://www.youtube.com/watch?v=ygrsIqWOh3Y)

---

## 📊 Progress

Track your progress by checking off tasks as you complete them!

When done with this phase, merge to `main` and move to `phase-2`.

---
*Generated by [RoadmapFlow](https://roadmapflow.com) 🚀*
