[![safelyolli.png](https://s7.postimg.org/4fh9ne72j/safelyolli.png)](https://postimg.org/image/ub106l8w7/)
# SafelyOlli
This project has been ideated and developed at HackPrinceton 2017. It is an add-on accessibility-cum-safety feature for IBM's autonomous bus - Olli. 


## Inspiration
With the advent of autonomous vehicles, there have been rising concerns of passenger's safety in driver-less cars. Currently, there is no mechanism in place for autonomous vehicles to check the health condition of on-board passengers.

## What it does
IBM's autonomous bus - Olli is our target platform. **Safely Olli** will monitor the pulse rate of the passenger through the sensors integrated into the seats.  
1. If the heart beats faster/slower than the normal pulse rate.  
 > Olli will ask the passenger if he/she needs medical attention.
2. Depending upon the response of the passenger - Olli will either drive to the Hospital or the destination.
 >If there is no reponse under 12 seconds, Olli automatically drives to the hospital.
3. Happy you..... Happy Olli.....

## How I built it
We used heartbeat sensor along with an arduino to check for the heartbeat and if there is an abnormal pulse rate, a message is sent to the Olli's driving module to drive to the nearest hospital. We programmed the arduino to measure the pulse rate by the heartbeat sensor and check for abnormalities in the collected data.

## Challenges I ran into
Some of the challenges involved in this project are:
1. Getting the heartbeat sensor to work smoothly with the arduino powered by a battery.
2. Achieving the accuracy in recorded pulse rate needed to check for abnormalities.
3. Integrating the sensors into the seat of the bus.
4. Complete packaging of the product to demonstration.

## Accomplishments that I'm proud of
Since this my first hackathon, I am proud that I made SOMETHING and completed the basic functionalities. However, here are a few things I am proud of:
* Achieving the accuracy in measuring the pulse rate of the passenger.
* Completely developed and packaged the product ready to be SHIPPED!

## What I learned
I got to learn a lot of stuff in this hackathon. Significant ones are:
* While writing this document, I learned the markdown language. It's easy
* How to play around with arduino and its wiring patterns.
* Soldering the wires and packaging the completed product.
* Using the 3D printer to print a micro model of **Olli**

## What's next for Safely Olli
We will add more features to this project and carefully look for loopholes in the product. We will be updating our product frequently. Sit tight and receive updates !


