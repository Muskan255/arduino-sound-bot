# Phase 2: Phase 2: Sensory Input and Chassis Integration

⏱️ **Estimated Duration:** 1 week

---

## 🎯 Milestone 1: Sound Sensor Integration

### Task 1: Wire Sound Sensor Module (LM393)

- [ ] **Status:** Not Started

**Description:**
Connect the LM393 sound sensor module to the Arduino Nano, specifically connecting its digital output (DO) pin to an Arduino digital input pin.

**✅ Definition of Done:**
> The LM393 sound sensor module is correctly wired to the Arduino Nano, with power, ground, and its digital output connected to an Arduino digital input pin.

**Concepts:** `Sound Sensor` `Sensor Interfacing` `Digital Read`

**📚 Resources:**
- 🔗 [How Does a Sound Sensor Work and how to Interface it with Arduino?](https://circuitdigest.com/microcontroller-projects/interfacing-sound-sensor-with-arduino)
- 🔗 [The Sound Weave Device - General Discussion - Sapien Medicine](https://forum.enlightenedstates.com/t/the-sound-weave-device/33520)
- 🎥 [How to Connect and Use Sound Sensor Module with Arduino + ...](https://www.youtube.com/watch?v=QzvV5Iu3Uc0)
- 🔗 [Using the Microphone Sound Sensor Module KY-038 with Arduino](https://www.phippselectronics.com/using-the-microphone-sound-sensor-module-ky-038-with-arduino/)
- 🎥 [How To Use A Sound Sensor With Arduino - YouTube](https://www.youtube.com/watch?v=a1Kp1OtSwu8)
- 🔗 [Arduino tutorial ", " url": "https://docs.keyestudio.com/projects/KS5005/en/latest/docs/Arduino/Arduino.html", "type": "doc"}, {"title": "Lesson 20 - Sound Sensor Module KY-038 - YouTube", "url": "https://www.youtube.com/watch?v=CbovaHqvdsM", "type": "video"}, {"title": "Answered: LM393 sound detector won't wake up Pro Mini from sleep", "url": "https://forum.arduino.cc/t/answered-lm393-sound-detector-wont-wake-up-pro-mini-from-sleep/282590", "type": "article"}]}``` backstory: I'm a helpful assistant that merges and ranks learning resources from multiple specialized search engines.Task: Wire Sound Sensor Module (LM393)Description: Connect the LM393 sound sensor module to the Arduino Nano, specifically connecting its digital output (DO) pin to an Arduino digital input pin.You have received resources from three specialized search engines:1. **Docs PSE** (Official guides and documentation): 6 resources2. **Code PSE** (Repositories and notebooks): 6 resources  3. **Video PSE** (Tutorial videos): 6 resourcesYour task:1. **Merge** all resources from the three sources, removing duplicates (same URL)2. **Rank** them by relevance to the task, quality, and learning value3. **Categorize** each resource with the appropriate type:- 'video': YouTube, Vimeo, or other video platforms- 'doc': Official documentation sites- 'repo': GitHub, GitLab, or other code repositories- 'article': Blog posts, tutorials, articles- 'other': Everything elsePrioritize:- Most relevant resources for learning the task- High-quality, authoritative sources- A good mix of resource types (docs, code, videos)- Official documentation and well-maintained repositoriesReturn the top 6-8 best resources, ranked from most to least relevant.Docs Resources:- Title: Answered: LM393 sound detector won't wake up Pro Mini from sleep  URL: https://forum.arduino.cc/t/answered-lm393-sound-detector-wont-wake-up-pro-mini-from-sleep/282590  Description: Jan 15, 2015 ... If i enable serial output , i can see that the A0 pin is sensing 1023 until a sound triggers the module and the led comes on and the signal ...- Title: Figure8: The connection of the sound module with Arduino (Henry's...  URL: https://www.researchgate.net/figure/Figure8-The-connection-of-the-sound-module-with-Arduino-Henrys-Bench-2015_fig4_305262308  Description: Download scientific diagram | Figure8: The connection of the sound module with Arduino (Henry's Bench, 2015). from publication: Low cost Sensor usability ...- Title: GP2Y0A21YK0F Infrared Distance Sensor and LM393 dual ...  URL: https://forum.arduino.cc/t/gp2y0a21yk0f-infrared-distance-sensor-and-lm393-dual-comparator/402514  Description: Aug 13, 2016 ... I am using two GP2Y0A21YK0F sensor for this purpose. It is working fine If I take analog readings and process that data with Arduino Nano. I ...- Title: Figure1: Arduino Uno Board displaying all the pins (B_E_N, 2016)  URL: https://www.researchgate.net/figure/Figure1-Arduino-Uno-Board-displaying-all-the-pins-B_E_N-2016_fig1_305262308  Description: Figure7: The sound sensor for Arduino (LM393 op-amp). +4 Figure8: The connection of the sound module with Arduino (Henry's... Low cost Sensor usability with ...- Title: Arduino tutorial — keyestudio WiKi documentation  URL: https://docs.keyestudio.com/projects/KS5005/en/latest/docs/Arduino/Arduino.html  Description: In this lesson, we will make a smart sound activated light using a sound sensor and an LED module. ... This flame sensor uses an analog pin and a digital pin.- Title: The Sound Weave Device - General Discussion - Sapien Medicine  URL: https://forum.enlightenedstates.com/t/the-sound-weave-device/33520  Description: May 9, 2022 ... ... Sound Sensor Arduino | Random Nerd Tutorials ||Guide for ... LM393 module, you should connect the OUT pin to an Arduino digital pin.Code Resources:- Title: How To Use A Sound Sensor With Arduino - YouTube  URL: https://www.youtube.com/watch?v=a1Kp1OtSwu8  Description: Jan 31, 2020 ... In this video I'm gonna teach you how to use a sound sensor with an Arduino Uno to control an led by making loud noises. ♢ ... Wires: https://amzn ...- Title: Answered: LM393 sound detector won't wake up Pro Mini from sleep  URL: https://forum.arduino.cc/t/answered-lm393-sound-detector-wont-wake-up-pro-mini-from-sleep/282590  Description: Jan 15, 2015 ... If i enable serial output , i can see that the A0 pin is sensing 1023 until a sound triggers the module and the led comes on and the signal ...- Title: Lesson 20 - Sound Sensor Module KY-038 - YouTube  URL: https://www.youtube.com/watch?v=CbovaHqvdsM  Description: Jan 9, 2019 ... Elegoo Arduino UNO R3 board · KY-038 Analog and Digital output Sound Sensor Module (KY-037 typically only has a Digital output) · Four female-to- ...- Title: Using the Microphone Sound Sensor Module KY-038 with Arduino  URL: https://www.phippselectronics.com/using-the-microphone-sound-sensor-module-ky-038-with-arduino/  Description: Feb 22, 2021 ... The KY-038 module has four pins. Pin, Description. A0, Analog Output. G, Ground. (+), +5V.- Title: SOUND SENSOR DATA ON ARDUINO SERIAL PLOTTER - YouTube  URL: https://www.youtube.com/watch?v=PYkzJQhFNlA  Description: Mar 20, 2020 ... The CZN-15E sound sensor with microphone is able to detect sound. This sensor or for example used in a so called ](https://www.youtube.com/watch?v=PYkzJQhFNlA)
- 🔗 [How Does a Sound Sensor Work and how to Interface it with Arduino?](https://circuitdigest.com/microcontroller-projects/interfacing-sound-sensor-with-arduino)

---

### Task 2: Read Sound Sensor Digital Output

- [ ] **Status:** Not Started

**Description:**
Write Arduino code to read the digital output of the sound sensor. Use the Serial Monitor to display its state (HIGH/LOW) when sound is detected.

**✅ Definition of Done:**
> The Serial Monitor displays 'Sound Detected' when a loud noise occurs near the sensor and 'No Sound' otherwise, based on the sensor's digital output.

**Concepts:** `Digital Input` `Sensor Reading` `Thresholding`

**📚 Resources:**
- 📖 [2.28 Sound Sensor Module - SunFounder's Documentations!](https://docs.sunfounder.com/projects/vincent-kit/en/latest/arduino/2.28_sound_sensor_module.html)
- 🔗 [Digital Sound sensor - Arduino Stack Exchange](https://arduino.stackexchange.com/questions/54489/digital-sound-sensor)
- 📖 [Arduino tutorial — Kidsbits Wiki documentation](https://wiki.kidsbits.cc/projects/KD0001/en/latest/Arduino/arduino.html)
- 🎥 [How To Use A Sound Sensor With Arduino - YouTube](https://www.youtube.com/watch?v=a1Kp1OtSwu8)
- 💻 [Grove Beginner Kit For Arduino - GitHub](https://github.com/Seeed-Studio/wiki-documents/blob/docusaurus-version/docs/Top_Brand/Arduino/Kit_with_Courses/Grove_Beginner_Kit_for_Arduino/Grove-Beginner-Kit-For-Arduino.md)
- 🎥 [Sound Sensor Arduino Tutorial - Elegoo The Most Complete Starter Kit](https://www.youtube.com/watch?v=1Oj_HkZAKms)
- 🔗 [Using sound sensor to serial print high,low - Arduino Forum](https://forum.arduino.cc/t/using-sound-sensor-to-serial-print-high-low/492594)
- 🎥 [SOUND SENSOR DATA ON ARDUINO SERIAL PLOTTER - YouTube](https://www.youtube.com/watch?v=PYkzJQhFNlA)

---

### Task 3: Implement Sound-Activated LED Toggle

- [ ] **Status:** Not Started

**Description:**
Modify the code so that a clap or loud noise triggers an LED connected to the Arduino to turn ON, and it turns OFF after a short delay if no more sound is detected.

**✅ Definition of Done:**
> An LED connected to the Arduino turns ON immediately upon a loud clap near the sound sensor and turns OFF after a configurable delay (e.g., 500ms) if no further loud sound is detected.

**Concepts:** `Event Handling` `Conditionals` `Debouncing`

**📚 Resources:**
- 📖 [Keyestudio Maker Learning Kit For Arduino](https://docs.keyestudio.com/projects/KS0080-KS0081-KS0082/en/latest/ks0080%2C81%2C82.html)
- 🔗 [Sound Activated LED Issue - LEDs and Multiplexing - Arduino Forum](https://forum.arduino.cc/t/sound-activated-led-issue/439680)
- 🔗 [Candle Blowing Project On and Off LEDs Using Fire and Sound](https://www.circuitschools.com/candle-blowing-project-on-and-off-leds-using-fire-and-sound/)
- 🔗 [Arduino Audio Reactive Desk Light - Hackster.io](https://www.hackster.io/haziq-azri/arduino-audio-reactive-desk-light-7ef416)
- 💻 [A simple Arduino trigger of the Adafruit Audio FX Sound Board](https://gist.github.com/stonehippo/308a5f5c49d4981ac976)
- 🎥 [How to Use Arduino Interrupts The Easy Way - YouTube](https://www.youtube.com/watch?v=SXZkX3cJqDs)
- 🔗 [Sound Reactive Cloud Lamp w/ "Lightning Mode" - Arduino Forum](https://forum.arduino.cc/t/sound-reactive-cloud-lamp-w-lightning-mode/447798)

---

## 🎯 Milestone 2: Chassis Assembly & Dual Motor Control

### Task 1: Assemble the Robot Chassis

- [ ] **Status:** Not Started

**Description:**
Construct the mobile robot chassis, attaching the DC motors and wheels according to the kit instructions.

**✅ Definition of Done:**
> The robot chassis is fully assembled, with both DC motors and wheels securely attached, forming a stable mobile platform.

**Concepts:** `Chassis Assembly` `Mechanical Assembly` `Robotics Hardware`

---

### Task 2: Mount Components on Chassis

- [ ] **Status:** Not Started

**Description:**
Securely mount the Arduino Nano, L298N motor driver, 9V battery, and sound sensor onto the assembled robot chassis.

**✅ Definition of Done:**
> All primary electronic components (Arduino, motor driver, sound sensor, battery) are firmly mounted on the chassis, and wires are neatly organized.

**Concepts:** `Mounting` `Component Placement` `Cable Management`

---

### Task 3: Implement Dual DC Motor Control for Movement

- [ ] **Status:** Not Started

**Description:**
Wire both DC motors to the L298N motor driver and write Arduino code to enable basic robot movements: forward, backward, turn left, turn right, and stop.

**✅ Definition of Done:**
> The robot can execute programmed commands to move forward, backward, turn left, turn right, and stop, with both motors responding correctly to maintain direction.

**Concepts:** `Differential Drive` `Robotics Kinematics` `Function Abstraction`

---

## 📊 Progress

Track your progress by checking off tasks as you complete them!

When done with this phase, merge to `main` and move to `phase-3`.

---
*Generated by [RoadmapFlow](https://roadmapflow.com) 🚀*
