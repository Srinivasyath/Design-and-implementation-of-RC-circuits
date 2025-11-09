# Design-and-implementation-of-RC-circuits
Designing of RC LPF circuit with cutoff frequency 1khz
Input sine signal with different frequencies are applied 
Observation:-
For input frequency f=100hz
Output waveform is sine signal without any amplitude attenuation and phase delay 
For input frequency f=1khz
Output waveform is sine wave with amplitude of 0.707v and phase delay is observed 
For input f=100khz
Output waveform is sine with amplitude of 0.2v
And phase delay is observed 

Designing of RC circuit with switch 
Input vdc=5v applied 
Observation:-
At t=0 to t=1 ms switch is off
Cap Start charging from 2.5v to 5v 
2.5v is voltage drop across the 1k ohm resistor 
At t=1ms to t=2ms switch on
Vout changes from 5 v to 2.5 v as capcitor discharge from 5v to 2.5v 
The output doesn't goes to 0v since it still connected with source
