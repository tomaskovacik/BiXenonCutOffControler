# BiXenonCutOffControler

Simple board which enable bi-xenon cutoff selenoid only if low beams are turned on or disable it when low beams are turned off. When your car is using [PWM](https://en.wikipedia.org/wiki/Pulse-width_modulation) to drive your high beam bulbs at ~30% to act as daytime driving lights, connecting bixenon cuttoff selenoid paralel to high beam bulb will cause nasty rattling noise of this selenoid. 

<img src="https://raw.githubusercontent.com/tomaskovacik/BiXenonCutOffControler/main/20210810_064935.jpg" />

# Schematics

Single Nchannel mosfet is turned on when low beams are enabled. This mosfet grounds one side of selenoid which is then turned on when high beams are used.

<img src="https://raw.githubusercontent.com/tomaskovacik/BiXenonCutOffControler/main/schematics.png" />

# In action

https://youtu.be/b0E2H7acrZI

<a href="https://www.tindie.com/stores/tomaskovacik/?ref=offsite_badges&utm_source=sellers_tomaskovacik&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>
