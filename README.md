# DC-Electronic-Load

This project was to make a simple DC electronic load. The load uses two IRFP460 Mosfets alowing for a maximum power of 160W and 400V. The control for the mosfets is simple using a 1mohm shunt and opamp to insure a constant current. As I did not want to spend money on a big heat sink I used an old CPU heatsink with a fan to remove the heat from the fets. I was intialy going to implment a simple system of just having the fan at max speed all the time however as a chalange I implmented a simple Propotinal control system. The fan that came with the heat sink was a four leaded type. This type of fan has three input wires and one ouput wire. The inputs are 12V, GND and a conrol signal the signal is about ??Hz and the duty cycle changes the fan speed. For the control system I used a TL494 a general PWM IC.

The Load 
![20230426_170632](https://user-images.githubusercontent.com/114579521/234475221-e32f96fc-aba6-4f5d-af1a-f4b2be759254.jpg)
