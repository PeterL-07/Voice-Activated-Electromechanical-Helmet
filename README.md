# Voice-Activated-Electromechanical-Helmet
This functional helmet, modeled after the Iron Man helmet, uses the DFRobot voice module to activate the opening and closing mechanism. The model's mechanism uses SG90 micro servo motors alongside a PCA9685 servo driver.

# Libraries
- <Wire.h>
- <DFRobot_2301Q.h>
- <Adafruit_PWMServoDriver.h>

# Instructions
- State "Jarvis" and wait for a response from the voice module.
- "Open mask" or "Close mask" should then direct an affirmative response.
- Mask should open/close based on corresponding voice inputs.
- Feature: Closing mask turns on LED lights located in the eyes. 
