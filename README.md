# Micro_Osci
This project is to develop a software tool, to view the signals in live, and to implement the most of oscilloscope features

IdeationPhase

## Goal / Mission / Vision
The goal is to create a resource ( software and microcontorller ) to measure a signal which help us to have a osilloscope at low cost. 


## Tech stack
1. QT ( for software GUI )
2. UART ( for transfering signal )
3. Microcontroller ( arduino nano )


## Arduino nano spec
Its maximum UART baud rate is 115200.
less consder the 255 sampler, which mean for single data we need a 8bit, at theory we can send 14.4k data in a seconds ( 14.4KHZ )

ATMEGA328p is operating in 8MHZ or 16MHZ. so this computation latency should be negligble. similarly for systems too.

## Tasks
### Phase - 1 ( MVP )
- [ ] Write a simple arduino code and check the graph in arduino IDE in plotter ( or serial monitor )
- [ ] Create a design for the Micro_Osci 
- [ ] Create a Micro_Osci application using QT ( GUI )
- [ ] bringing the live graph on the screen in QT application
- [ ] Finding frequency and amplitude display feature
- [ ] record features
- [ ] zoom, trigger features

## Learning
- By doing this project we get better knowledge on the Arduino, QT application, signal processing ( etc ... )

## Project similar to our idea
1. [Free Master PC](https://www.nxp.com/design/design-center/software/development-software/freemaster-run-time-debugging-tool:FREEMASTER) tool from nxp for debugging
2. [arduino oscillo scope in arduino ide plotter](https://projecthub.arduino.cc/Meeker6751/8d0be83b-8696-492d-9f1e-46fe9c5e2248)
3. [arduino oscilloscope using oled display](https://projecthub.arduino.cc/siliconvalley4066/arduino-oled-dual-channel-oscilloscope-197863)
4. [from instructables, similar to our idea application is built in processing](https://www.instructables.com/Oscilloscope-Arduino-Processing/)
5. 

### How our project is unique in the above projects