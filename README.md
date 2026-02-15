# Phase 4: Phase 4: Integration, Refinement, and Finalization

⏱️ **Estimated Duration:** 1 week

---

## 🎯 Milestone 1: Full System Integration

### Task 1: Integrate All Modules into a Cohesive System

- [ ] **Status:** Not Started

**Description:**
Combine all developed code modules (sound detection, motor control, directional logic) into a single, well-structured Arduino program. Ensure smooth transitions between states.

**✅ Definition of Done:**
> All code modules are integrated into one Arduino sketch, and the robot successfully demonstrates its core sound-chasing behavior from power-on without errors.

**Concepts:** `System Integration` `Modular Programming` `Finite State Machine (FSM)`

**📚 Resources:**
- 📖 [Arduino Tutorial — Kidsbits Wiki documentation](https://wiki.kidsbits.cc/projects/KD0003/en/latest/Arduino/arduino.html)
- 🎥 [Motor Drivers vs. Motor Controllers - Video Tutorial Australia](https://core-electronics.com.au/videos/motor-drivers-vs-motor-controllers)
- 🎥 [Arduino Beginners Getting Started With NEMA 17 Stepper Motor ...](https://www.youtube.com/watch?v=xkH2EJglwbk)
- 📖 [KS0349 Keyestudio 48 in 1 Sensor Kit](https://docs.keyestudio.com/projects/KS0349/en/latest/KS0349.html)
- 🔗 [Getting Started with PlatformIO - Better than the Arduino IDE](https://dronebotworkshop.com/platformio/)
- 🎥 [HC-SR04 ULTRASONIC SENSOR - WHAT it is and HOW to use it.](https://www.youtube.com/watch?v=1E4TDZC-xaY)
- 💻 [MicrochipTech/avrfreaks-projects - GitHub](https://github.com/MicrochipTech/avrfreaks-projects)
- 📖 [KS0399 KS0400 KS0401 Keyestudio 37 in 1 Sensor Kit V2.0 for ...](https://docs.keyestudio.com/projects/KS0399-KS0400-KS0401/en/latest/KS0399%2C0400%2C0401.html)

---

### Task 2: Implement Visual Feedback for States

- [ ] **Status:** Not Started

**Description:**
Add LED indicators or serial output to clearly show the robot's current state (e.g., 'listening', 'turning', 'moving').

**✅ Definition of Done:**
> The robot uses an LED (or a combination of LEDs) to visually indicate its active state (e.g., solid for 'listening', blinking for 'turning', fast blink for 'moving forward').

**Concepts:** `User Feedback` `Debugging Aids` `State Indication`

**📚 Resources:**
- 💻 [ScionResearch/tof-proximity-sensor - GitHub](https://github.com/ScionResearch/tof-proximity-sensor)
- 💻 [Smart Staircase Lighting System - GitHub](https://github.com/Aryanpanwar10005/smart_staircase_lighting_system)
- 🔗 [Using Serial.print and digitalWrite in Same Arduino Script](https://stackoverflow.com/questions/43881852/using-serial-print-and-digitalwrite-in-same-arduino-script)
- 🎥 [Arduino Workshop - Chapter 4 - Using EEPROM - Core Electronics](https://core-electronics.com.au/videos/arduino-workshop-chapter-4-using-eeprom)
- 📖 [KS0349 Keyestudio 48 in 1 Sensor Kit](https://docs.keyestudio.com/projects/KS0349/en/latest/KS0349.html)
- 🔗 [Arduino - Turn LED ON and OFF With Button - The Robotics Back-End](https://roboticsbackend.com/arduino-turn-led-on-and-off-with-button/)
- 🎥 [Arduino - Turn LED On and Off With Push Button - YouTube](https://www.youtube.com/watch?v=ZoaUlquC6x8)
- 📖 [6. Arduino Programming Project — xArm AI v1.0 documentation](https://docs.hiwonder.com/projects/xArm_AI/en/latest/docs/6.Arduino_Programming_Project.html)

---

## 🎯 Milestone 2: Performance Tuning & Finalization

### Task 1: Calibrate Motor Speeds and Turning Precision

- [ ] **Status:** Not Started

**Description:**
Adjust motor speeds and turning durations in the code to ensure smooth, precise, and consistent movement for effective sound chasing.

**✅ Definition of Done:**
> The robot's turns are consistent in angle, and its forward movement is smooth and straight, optimized for its chassis and motors, after calibration.

**Concepts:** `Calibration` `PID Control (conceptual)` `Fine-tuning`

**📚 Resources:**
- 📖 [Controller 

ODrive Documentation 0.6.11 documentation](https://docs.odriverobotics.com/v/latest/manual/control.html)
- 💻 [ArminJo/PWMMotorControl: Arduino library to control ... - GitHub](https://github.com/ArminJo/PWMMotorControl)
- 🎥 [Arduino Line Follower - Code Development #1 - YouTube](https://www.youtube.com/watch?v=w3bE3ygJMx8)
- 🎥 [Prime Tutorials Part One: Gyro Turning! - YouTube](https://www.youtube.com/watch?v=uqo1KO6oDuE)
- 🔗 [Wheels, Encoders, Hardware, and Software - Theory vs Reality](https://forum.dexterindustries.com/t/wheels-encoders-hardware-and-software-theory-vs-reality/5319)
- 🎥 [Brushless Motor Control with Arduino (slow rotation) Open loop](https://m.youtube.com/watch?v=_aAwbQtJsLo&t=0s)
- 🔗 [Gyro for Turning? - Programming - Arduino Forum](https://forum.arduino.cc/t/gyro-for-turning/258668)
- 💻 [More precise torque control at low speeds with external encoder #210](https://github.com/EmanuelFeru/hoverboard-firmware-hack-FOC/issues/210)

---

### Task 2: Optimize Sound Sensor Sensitivity and Thresholds

- [ ] **Status:** Not Started

**Description:**
Fine-tune the sound sensor's physical potentiometer and software thresholds to achieve reliable detection of claps/loud noises while minimizing false positives from ambient background noise.

**✅ Definition of Done:**
> The robot reliably detects claps within a reasonable range (e.g., 1-2 meters) and avoids triggering on common background noises in a typical room environment.

**Concepts:** `Sensor Calibration` `Noise Immunity` `Threshold Adjustment`

**📚 Resources:**
- 💻 [KD0001-Coding-box-for-Arduino/Arduino/arduino.md at main - GitHub](https://github.com/kidsbits/KD0001-Coding-box-for-Arduino/blob/main/Arduino/arduino.md)
- 🔗 [Sound-Activated Outlet - Make Magazine](https://makezine.com/projects/sound-activated-outlet/)
- 🎥 [How To Use A Sound Sensor With Arduino - YouTube](https://www.youtube.com/watch?v=a1Kp1OtSwu8)
- 📖 [KS0349 Keyestudio 48 in 1 Sensor Kit](https://docs.keyestudio.com/projects/KS0349/en/latest/KS0349.html)
- 📖 [KS4009 KS4010 Keyestudio Micro: bit 45 in 1 Sensor Learning Kit](https://docs.keyestudio.com/projects/KS4009-KS4010/en/latest/KS4009-KS4010.html)
- 🔗 [Sound Sensor Pi PICO | raspberry pi pico tutorial - Hackster.io](https://www.hackster.io/Techatronic/sound-sensor-pi-pico-raspberry-pi-pico-tutorial-fb401e)
- 🔗 [Sound Activate Switch Project - All About Circuits Forum](https://forum.allaboutcircuits.com/threads/sound-activate-switch-project.144651/)
- 🔗 [musical beat detection with microphone sensor - Arduino Forum](https://forum.arduino.cc/t/musical-beat-detection-with-microphone-sensor/584558)

---

### Task 3: Finalize Wiring and Secure Components

- [ ] **Status:** Not Started

**Description:**
Perform a final check of all wiring connections, ensure components are securely fastened, and tidy up any loose wires for a robust and safe final build.

**✅ Definition of Done:**
> All wiring connections are robust, components are securely mounted without wobble, and the robot's internal structure is neat and organized, ready for demonstrations.

**Concepts:** `Hardware Reliability` `Safety` `Professional Build`

**📚 Resources:**
- 🎥 [#231 7 Tricks on how to wire your Project (e.g. Arduino ... - YouTube](https://www.youtube.com/watch?v=uYf7vFREV98)
- 🎥 [Header Pin Connections for Raspberry Pi, Arduino, ESP32, STM32 ...](https://www.youtube.com/watch?v=JFIR4xJmBjA)
- 🎥 [How to use Adafruit DC & Stepper Motor HAT - Core Electronics](https://core-electronics.com.au/videos/how-to-use-adafruit-dc-stepper-motor-hat-controlling-dc-and-stepper-motors-with-a-raspberry-pi-)
- 🔗 [Getting Ugly, Dead Bugs, And Going To Manhattan | Hackaday](https://hackaday.com/2016/05/04/getting-ugly-dead-bugs-and-going-to-manhattan/)
- 📖 [KS0349 Keyestudio 48 in 1 Sensor Kit](https://docs.keyestudio.com/projects/KS0349/en/latest/KS0349.html)
- 🎥 [Make a TINY Arduino Drone with FPV Camera - Will It Fly? - YouTube](https://www.youtube.com/watch?v=Sa6EslOHsI0)
- 🔗 [Build an Art Bot - Creative Robotics for Kids - STEAM Powered Family](https://www.steampoweredfamily.com/diy-art-bot/)

---

## 📊 Progress

Track your progress by checking off tasks as you complete them!

When done with this phase, merge to `main` and move to `phase-5`.

---
*Generated by [RoadmapFlow](https://roadmapflow.com) 🚀*
