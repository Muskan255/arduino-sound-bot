# Phase 3: Phase 3: Sound-Driven Logic and Behavior

⏱️ **Estimated Duration:** 1 week

---

## 🎯 Milestone 1: Sound Detection Logic Integration

### Task 1: Combine Sound Detection with Movement Logic

- [ ] **Status:** Not Started

**Description:**
Integrate the sound detection code with the dual motor control code. The robot should stop whenever a loud sound is detected.

**✅ Definition of Done:**
> When a loud sound is detected by the sound sensor, the robot (if moving) immediately stops all motor activity.

**Concepts:** `Integration` `Conditional Logic` `State Management`

**📚 Resources:**
- 📖 [Arduino Tutorial — Kidsbits Wiki documentation](https://wiki.kidsbits.cc/projects/KD0003/en/latest/Arduino/arduino.html)
- 💻 [An obstacle-avoiding robot using an ultrasonic sensor and ... - GitHub](https://github.com/Awais-Asghar/Obstacle-Avoiding-Robot-using-Ultrasonic-Sensor)
- 🎥 [Control a DC Motor with an Ultrasonic Sensor and Arduino - YouTube](https://www.youtube.com/watch?v=fsC7CB5IQOc)
- 📖 [About Me Auriga - Makeblock Help Center](https://support.makeblock.com/hc/en-us/articles/4412149618327-About-Me-Auriga)
- 📖 [SyRen 25 - Ultrasonic Sensor to Emergency Stop - Robot Parts](https://community.robotshop.com/forum/t/syren-25-ultrasonic-sensor-to-emergency-stop/78186)
- 📖 [Have robot, won't travel? (solved) - General Guidance - Arduino Forum](https://forum.arduino.cc/t/have-robot-wont-travel-solved/142811)

---

### Task 2: Implement Sound Burst Detection

- [ ] **Status:** Not Started

**Description:**
Refine the sound detection to specifically look for a 'burst' of sound (e.g., a clap) rather than continuous noise, using a short duration check.

**✅ Definition of Done:**
> The robot's logic can differentiate a single, short loud sound (like a clap) from sustained background noise, triggering an event only for the burst.

**Concepts:** `Pulse Detection` `Timing` `Noise Filtering`

**📚 Resources:**
- 🔗 [An Arduino Triggers A Flash With Sound - Hackaday](https://hackaday.com/2024/10/15/an-arduino-triggers-a-flash-with-sound/)
- 🔗 [A Technological Review of Wearable Cueing Devices Addressing ...](https://www.mdpi.com/1424-8220/19/6/1277)
- 💻 [KS0505 Keyestudio STEM Starter Kit with plus board - GitHub](https://github.com/keyestudio/KS0505-STEM-Starter-Kit-with-PLUS-Board/blob/master/KS0505.md)
- 📖 [Arduino_C_Tutorial(Windows) — Raspberry Pi Pico Ultimate Starter ...](https://docs.keyestudio.com/projects/KS3020/en/latest/C-windows/C-windows.html)
- 📖 [Keyestudio Maker Learning Kit For Arduino](https://docs.keyestudio.com/projects/KS0080-KS0081-KS0082/en/latest/ks0080%2C81%2C82.html)
- 📖 [SparkFun Inventor's Kit Experiment Guide - v4.1](https://learn.sparkfun.com/tutorials/sparkfun-inventors-kit-experiment-guide---v41/all)

---

## 🎯 Milestone 2: Directional Movement Algorithms

### Task 1: Develop Basic Turning Algorithm for Sound

- [ ] **Status:** Not Started

**Description:**
Implement a simple algorithm where upon detecting a sound, the robot performs a short turn (e.g., 45 degrees left) and then checks for sound again. This simulates a basic 'search' behavior.

**✅ Definition of Done:**
> Upon detecting a sound, the robot executes a predetermined turn (e.g., 45-degree rotation), then pauses to listen for subsequent sound detections.

**Concepts:** `Directional Logic` `Trial and Error` `Algorithm Design`

**📚 Resources:**
- 📖 [Sound localization for my robot - #11 by Johan_Ha - Arduino Forum](https://forum.arduino.cc/t/sound-localization-for-my-robot/1302078/11)
- 🔗 [Directional hearing for Linux robot? - Robotics Stack Exchange](https://robotics.stackexchange.com/questions/3021/directional-hearing-for-linux-robot)
- 🎥 [How to Control a 12V Motor with Arduino: Easy Wiring & Code ...](https://www.youtube.com/watch?v=NIx_KycgOJM)
- 🎥 [Get Started with Ultrasonic Sensors and Arduino: Step-by ... - YouTube](https://www.youtube.com/watch?v=ZqQgxgnH9wg)
- 🔗 [Autonomous Path Finding Robot – IJERT](https://www.ijert.org/autonomous-path-finding-robot)
- 🎥 [I made a SUPER FAST Line Follower Robot Using PID! - YouTube](https://www.youtube.com/watch?v=QoNkpnpvEqc)
- 📖 [Line follower With Sonar Sensor - General Guidance - Arduino Forum](https://forum.arduino.cc/t/line-follower-with-sonar-sensor/1170229)

---

### Task 2: Refine Directional Turn and Move

- [ ] **Status:** Not Started

**Description:**
Modify the algorithm so that after turning towards a sound, the robot moves forward for a short distance before listening for the next sound, creating a chasing behavior.

**✅ Definition of Done:**
> After detecting a sound and performing a turn, the robot consistently moves forward for a specified duration (e.g., 1 second) before entering its next listening phase.

**Concepts:** `Sequential Actions` `Autonomous Behavior` `Iteration`

**📚 Resources:**
- 📖 [Light-Seeking Robot - SparkFun Learn](https://learn.sparkfun.com/tutorials/light-seeking-robot/all)
- 🎥 [How To Make Arduino Human Following Robot - YouTube](https://www.youtube.com/watch?v=yAV5aZ0unag)
- 🎥 [Ultrasonic Sensor | Object Following Arduino Robot - YouTube](https://www.youtube.com/watch?v=JXIbxX-Wtgw)
- 📖 [Implementation of an Artificially Empathetic Robot Swarm - MDPI](https://www.mdpi.com/1424-8220/24/1/242)
- 💻 [How to make an enemy follow the player in pygame? - Stack Overflow](https://stackoverflow.com/questions/20044791/how-to-make-an-enemy-follow-the-player-in-pygame)
- 📖 [A Compact Magnetic Field-Based Obstacle Detection and ... - MDPI](https://www.mdpi.com/1424-8220/17/6/1231)
- 🔗 [Designing An Advanced Autonomous Robot: Goose | Hackaday](https://hackaday.com/2019/08/08/designing-an-advanced-autonomous-robot-goose/)

---

## 📊 Progress

Track your progress by checking off tasks as you complete them!

When done with this phase, merge to `main` and move to `phase-4`.

---
*Generated by [RoadmapFlow](https://roadmapflow.com) 🚀*
