# Linear-Predictive-Coder
MATLAB Implementation of LPC algorithm for speech signal

# Why LPC?
In communication systems it is often necessary to transmit audio(speech) signal in compressed or encoded form because of bandwidth limitation of the channel. In this regard, ‘Linear predictive coding(LPC)’ is an effctive method of speech coding at a low bit-rate.

# Features
 ** Analysis/Encoding phase,Synthesis/Decoding phase.
 
 **Human voice modelled with all-pole filter.

** LPC parameters(filter coefficients, pitch, gain etc) extraction at the decoding phase.

** Non-overlapping frames of 30 milliseconds in duration

# How To Run
** Make sure MATLAB(latest version) is installed

** Put both files(LPC.m with .mp3 file) in the same folder
 
** Open LPC.m file and run it. 

## Comments
Different audio (.mp3) files can be coded/decoded by changing the input file name in the code.
