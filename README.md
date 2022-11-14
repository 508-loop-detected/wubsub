# wubblesubble

<img src="wubsub.jpg" width=400>

A subharmonic oscillator with CV control over the mix. There is one audio input -- takes in the signal from a VCO. There is one audio output, which outputs the mix of some/all of the subharmonics with the original. There are six CV inputs which provide CV control over the mix. 

The channels are, from top to bottom:
 - original input signal
 - square wave a fifth below original
 - square wave an octave below original
 - square wave a fifth plus an octave below original
 - square wave two octaves below original
 - square wave a fifth plus two octaves below original

The pots in the left column provide manual control over the amount of each of the above in the mix. The pots in the right column control the amount of CV influence over that channel's presence in the mix. 

The switches control low-pass filters -- up for a moderate amount of filtration, down for more, middle for none.

This module, like many of my modules, uses 2mm-pitch male/female headers. Be sure you order/use the right thing!

Most ICs are SOIC 8/14/16; all passives are 0805. The BOMs prefixed with `fixed` are easier to read; the others can be used along with the Pick-and-place and gerber files to order PCBs.

The input section using a 4093 to double the frequency of the input waveform is shamelessly borrowed, as most great Eurorack DIY things are, from Ken Stone. 
