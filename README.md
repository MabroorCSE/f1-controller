# F1-Controller
Aiming to build a controller inspired by Formula 1 that will be used in a top-down view racing game that I develop in Pygame. This project is a way for me to learn the core of Computer Systems Engineering (CSE) which is what I plan to do.

## Materials Used/Plan to use
- Arduino UNO (1)
- Arduino MEGA (1)
- OLED Display Module (1)
- Mini toggle switches (2)
- WS2812B 5050 Addressable light sticks (2)
- Joystick (2)
- Arcade style buttons (TBD based on design)
- Portable Power Supply. Either LiPo battery or a simple USB power bank (1-2)

## Controller Features
- This controller is going to be inspired by F1 steering wheels
- It will be symmetrical for simplicity
- Includes 2 joysticks. 1 to move around, have not decided the other one
- Includes 2 metal toggle switches for a more professional look. 1 for power on/off, have not decided the other one
- A large OLED screen at the top of the controller displaying stats such as: lap, lap time, speed, gear, etc
- A row of LEDs above the OLED screen to mimic the shift lights on F1 steering wheels
- Buttons will be placed across the controller depending on comfortability and reach based on the casing of the controller

## The Game
- The racing game will be a top-down view of a 2D map
- There will be roads and grass as well
- I will try to add some animations so it does not look too stagnant
- I don't plan on having opponents yet, just a time trial
- If the player goes off track, slow down the car. Also, begin a 3 second timer on the LED bar on the controller itself, make it all red and start going backwards, if the player is not back in that time, reset or go back to checkpoint. Not sure yet which one.
- Potentially have one of the buttons show a large scale map of the track with an icon showing where player is

## Goal
- Design the encasing of the controller in CAD and 3D print it
- Wire and hook up each component taking voltage regulations into account
- Program the game (probably just 2D) in Pygame and ensure the controller works properly

## Timeline
- Start by simply learning the skills (CAD, Arduino, Programming)
- I have some experience in programming and I just started learning Arduino and wiring, I will have to learn CAD as well
- Mess around in Arduino. Small projects to just get the ball rolling
- Do the same for CAD, start with very simple things
- Begin experimenting with Pygame. Never used it before, only Java Swing
- Once I'm comfortable with all 3 skills, start combining them together until, eventually, I'm ready for the main project
- I planned for this to be a project in Summer 2025 before I head off to university, but it seems I'll have to continue this there

## Demos
- [First LED](https://youtube.com/shorts/aPd60NuJWBU)
- [Button input](https://youtube.com/shorts/VEi75wpWUuE)
- [Joystick-controlled LED brightness](https://youtube.com/shorts/zbac8oJvNCg)
- [F1 shift light sequence](https://youtube.com/shorts/GQSaH0udJnA)

## Status
Paused after initial prototyping (July 2025). Progress logs are in [`docs/progress`](docs/progress).
