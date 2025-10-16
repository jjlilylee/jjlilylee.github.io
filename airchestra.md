# The Airchestra Project

## 📋 Project Description
Traditional music education often depends on physical instruments and precise motor control, creating barriers for students with mobility or dexterity challenges. Airchestra reimagines how students engage with sound by transforming hand gestures into music, color, and rhythm.

Using two ultrasonic rangefinders, students can play and shape sound directly in the air. One sensor detects the distance of the hand to control pitch, while the other modulates volume, allowing for dynamic expression without physical contact. A NeoPixel light changes color with each pitch, offering visual reinforcement that bridges auditory and visual learning. In addition to tone and volume control, Airchestra includes an interactive metronome powered by an RC servo motor. With the press of a button, students can start or stop the metronome and use a potentiometer to adjust the tempo. 
<br><br>
![Airchestra Notes Color](images/oriented_airchestra_notes.png)
![Airchestra Dynamics](images/airchestra_dynamics.png)
<br><br>
By using one hand to control pitch and the other hand to control volume, students can develop skills fundamental to orchestral conducting, such as independent hand coordination, expressive dynamics, and precise control of musical phrasing. This multisensory design not only enhances accessibility in music classrooms but also provides a creative, engaging way for choir students to connect solfege hand motions with sound and color, bridging motion, music, and inclusivity.

<video controls width="640">
  <source src="images/combined.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## 🛠️ Technical Overview

| **Category** | **Details** |
|---------------|-------------|
| **Microcontroller** | Raspberry Pi Pico |
| **Input Components** | - Ultrasonic Rangefinder (Pitch Control)<br>- Ultrasonic Rangefinder (Volume Control)<br>- Potentiometer (Tempo Adjustment)<br>- Push Button (Metronome Activation) |
| **Output Components** | - Speaker, Amplifier (Audio Output)<br>- NeoPixel RGB LED (Visual Feedback)<br>- RC Servo Motor (Metronome Arm) |
| **Core Functions** | - Maps hand distance (ultrasonic input) to pitch and volume<br>- Synchronizes LED color transitions with pitch frequency<br>- Uses potentiometer to adjust metronome tempo<br>- Activates/deactivates metronome via button press |
| **Programming Language** | CircuitPython |
| **Educational Impact** | - Encourages inclusive participation in music education<br>- Reinforces pitch and rhythm learning through multisensory feedback<br>- Enables gesture-based musical interaction |

## 👷‍♀️ System Architecture

![Airchestra Block Diagram](images/SystemArchitecture.png)
<br><br>

## 💡 Circuit Diagram

## 👩‍💻 Code
