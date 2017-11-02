# Routing set up in the Rack Mixer

What is routed where in the rack mixer is described below.

## Home

The home page sets up where the rack mixer's processing channels get their inputs from.

We give it the following signals:
- **1-8** _AES50 A1-8_ The stagebox's first 8 inputs. These are used when locally mixing, they are muted when remotely mixing with the main mixer.
- **9-16** _AES50 A9-16_ The stagebox's second 8 inputs. These are used when locally mixing, they are muted when remotely mixing with the main mixer.
- **17-24** _AES50 B1-8_ The main mixer's monitor outputs. When set up for use with the main mixer, these are mixed directly to the the rack mixer's output busses, mapped 1:1.
- **25-32** _AES50 B9-16_ The main mixer's speaker outputs. When set up for use with the main mixer, these are mixed directly to the the rack mixer's output busses, mapped 1:1.
- **Aux in Remap** _Local 1-4_ This makes the rack mixers first 4 local inputs (kitchen bluetooth and radio mic) appear on the Aux inputs.

![Routing home screenshot](/images/routing/800x600/home.jpg)

## Out 1-16

The Out 1-16 page sets out where the internal outputs get their signals from.

We give it the following signals:
- **1-8** _MixBus 1-8_ The rack mixer's monitor busses. These will be mixed from the local monitor mixes and remote (main mixer) monitor mixes according to set up.
- **9-16** _MixBus 9-16_ The rack mixer's speaker busses. These will be mixed from the local speaker mixes and remote (main mixer) speaker mixes according to set up.

![Routing outputs screenshot](/images/routing/800x600/mix_out.jpg)

## AES50 A outputs

AES550 A is the stagebox connection. These are what the rack mixer sends to the stagebox.

We send it the following signals:
- **1-8** _Out 1-8_ The rack mixer's monitor outputs. These are usually what the stagebox uses.
- **9-16** _Out 9-16_ The rack mixers's speaker outputs. Unlikely to be useful, unless different speakers are being run from the stage box.
- **17-24** _AES50 B1-8_ The main mixer's monitor outputs. These are usually mixed into the rack mixer's monitor outputs by the rack mixer, but can be used directly by setting the stage box to use these outputs.
- **25-48** These aren't really useful, but are probably the most sensible to send down the wire.

![AES50 A screenshot](/images/routing/800x600/AES_A.jpg)

## AES50 B outputs

AES5-50 B is the mixer connection. These are what the rack mixer sends to the main mixer.

We send it the following signals:
- **1-8** _AES50 A1-8_ The first 8 inputs on the stagebox. This is how the main mixer gets to the stagebox inputs.
- **9-16** _AES50 A9-16_ The second 8 inputs on the stagebox. This is how the main mixer gets to the stagebox inputs.
- **17-24** _Local 1-8_ The first 8 inputs on the back of the rack mixer. This lets the main mixer get to the radio mic, bluetooth box etc.
- **25-32** _Local 9-16_ The second 8 inputs on the back of the rack mixer. This lets the main mixer get anything else _not yet_ plugged into the rack mixer.
- **33-40** _AUX1-6/MON_ The aux inputs to the mixer, and the headphone output. This is how the main mixer gets to the video inputs.
- **41-48** _Out 1-8_ The rack mixer's monitor outputs. This generally isn't used, but could let an iPad be used for monitor mixing. **Do not mix these back into the main mixer's monitor outputs, it will feedback.**

![AES50 B screenshot](/images/routing/800x600/AES_B.jpg)

## XLR out

The XLR out page sets out where the XLR outputs on the back of the mixer get their signals from. We use these for the speaker outputs going to the amps and induction loop.

We give it the following signals:
- **1-4** _Out 9-12_ The speaker outputs, as mixed by the rack mixer (see Out 1-16).
- **5-8** _Out 13-16_ The speaker outputs, as mixed by the rack mixer (see Out 1-16).

![Routing XLR outputs screenshot](/images/routing/800x600/XLR_out.jpg)
