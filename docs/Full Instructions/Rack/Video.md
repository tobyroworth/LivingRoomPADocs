# Video

Inside the rack are three devices for the video system - a HDMIbaseT HMDI over cat5 receiver, an HDMI audio de-embedder and an HDMI splitter.

The remainder of the system is made up of a HDBaseT HDMI over cat5 transmitter and two TVs.

## What is HDBaseT

HDBaseT is a way of sending video and audio (amongst many other things) over cat5.

## HDBaseT Transmitter

This takes an HDMI or VGA signal and converts it to HDMIbaseT.

For VGA, it takes in an analogue audio signal through a 3.5mm jack. For HDMI, the audio is embedded in the HDMI signal.

## Patch Bay

The HDBaseT signals will usually go through the patch bay.

## HDBaseT Receiver

This takes the signal from the HDMIbaseT Transmitter and converts it back into HDMI.

The box also splits out the analogue audio signal if the VGA stream was used. This goes into `aux 7` and `aux 8` on the rack mixer (note both video audio signals go into the same input in the desk).

## HDMI Audio De-embedder

This splits the audio out of the HDMI stream to send it through the PA speakers.  This goes into `aux 7` and `aux 8` on the rack mixer (note both video audio signals go into the same input on the desk).

The audio signal doesn't carry on to the TVs. This is selected by using the DIP switch setting that crosses over, embedding the input analogue signal (which isn't plugged in, and therefore silent) onto the HDMI output and sending the digital HDMI input audio onto the analogue output. _Note that the other DIP switch settings don't do this, the crossover setting is required._

## HDMI Splitter

This takes the HDMI signal in, and sends it to two HDMI outputs, one per TV. This is where the TV cables plug in.

## TVs

Just normal TV screens, with an HDMI signal plugged into one of their inputs.
