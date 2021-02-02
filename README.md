# ratatouille~
## a Pure Data abstraction, pythagorean ratio pitch sequencer, ratatouille~.pd

A two-channel integer sequencer, each channel with two rows of low whole numbers that are compared to one another using the same mathematics Pythagoras did to explain just intonation.

As the sequencer rolls along, the integers change, sometimes at different rates, and they change ratio relationship to each other. They can be locked to one octave, slewed for ornamentation, divided, offset.

The two channels can be used as a left and right voice, or a bass and treble. The ratios need to be compared to a pitch value before they can be to be sent to an oscillator, so also accessible are the fundamental frequency tones, as drones.

It was an experiment, mostly a search for a way to produce melodies in just intonation without having to program all the scales, but it turned into something really fun, and some of the idiosyncrasies have brought up sounds of bagpipes, bells, lots of unexpected things.
credits

## For audio examples
You'll find album at https://nicoloscolieri.bandcamp.com/album/ratatouille. It is a gathering of the little recordings I made while I was developing the patch. I ran the pitches out to the hertz inputs of multiple osc~ objects, sometimes feeding them back into one another, combining intervals, sequenced ratios, the fundamental... After adding reverb in Ableton, I bounced the tracks to a cassette tape, then digitized the tape.

## Installation
To run this software, you'll need to have Pure Data installed. PD can be downloaded at https://puredata.info/downloads/pure-data
