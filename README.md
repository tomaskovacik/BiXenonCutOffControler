# BiXenonCutOffControler

<img src="https://raw.githubusercontent.com/tomaskovacik/BiXenonCutOffControler/main/20210721_141458.jpg"/>

Simple board which enable bi-xenon cutoff selenoid only if low beams are turned on or disable it when low beams are turned off. When your car is using [PWM](https://en.wikipedia.org/wiki/Pulse-width_modulation) to drive your high beam bulbs at ~30% to act as daytime driving lights, connecting bixenon cuttoff selenoid paralel to high beam bulb will 
will cause nasty rattling noise of this selenoid. 

# Schematics

Single Nchannel mosfet is turned on when low beams are enabled. This mosfet grounds one side of selenoid which is then turned on when high beams are used.

<img src="https://raw.githubusercontent.com/tomaskovacik/BiXenonCutOffControler/main/schematics.png" />
