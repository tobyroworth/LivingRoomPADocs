# Routing set up in the Main Mixer

What is routed where in the main mixer is described below.

## Home

The home page sets up where the main mixer's processing channels get their inputs from.

We give it the following signals:
- **1-8** _AES50 A1-8_ The stagebox's first 8 inputs.
- **9-16** _AES50 A9-16_ The stagebox's second 8 inputs.
- **17-24** _AES50 A17-24_ The rack mixers local XLR inputs, such as the bluetooth and radio mic.
- **25-32** _Local 1-8_ The first 8 XLRs on the back of the main mixer.
- **Aux in Remap** _Aix ins_ Leaves aux ins as-is.

![Routing home screenshot](/images/routing/800x600/mixer_home.jpg)

## Out 1-16

The Out 1-16 page sets out where the internal outputs get their signals from.

We give it the following signals:
- **1-8** _MixBus 1-8_ The mixer's monitor busses.
- **9** _Main L_ Sends the mixer's L mix to the left speaker.
- **10** _Main R_ Sends the mixer's R mix to the right speaker.
- **11** _Main M/C_ Sends the mixer's C mix to the front fill speaker.
- **12** _OFF_ Not used. Will eventually go to the speaker above the cafe area
- **13** _Main M/C_ Sends the mixer's C mix to the subwoofer.
- **14** _OFF_ Not used. Will eventually go the the speaker above the entrance.
- **15** _Main M/C_ Sends the mixer's C mix to the induction loop.
- **16** _OFF_ Not used.

![Routing outputs screenshot](/images/routing/800x600/mixer_mix_out.jpg)

## AES50 A outputs

AES550 A is the connection back to the rack mixer connection. These are what the main mixer sends back to the rack mixer.

We send it the following signals:
- **1-8** _Out 1-8_ The main mixer's monitor outputs. The rack mixer routes/mixes these to the stagebox.
- **9-16** _Out 9-16_ The main mixers's speaker outputs. The rack mixer routes/mixes these to the amps.
- **17-48** These aren't really useful, but are probably the most sensible to send down the wire.

![AES50 A screenshot](/images/routing/800x600/mixer_AES_A.jpg)

## AES50 B outputs

AES5-50 B isn't usually used, so no specific set up has been performed.

## XLR out

The XLR out page sets out where the XLR outputs on the back of the mixer get their signals from. We use these for the speaker outputs going to the amps and induction loop.

We give it the following signals:
- **1-4** _Out 1-4_ The monitor outputs, in case it is more convenient to plug monitors into the mixer than the stagebox.
- **5-8** _Out 5-8_ The monitor outputs, in case it is more convenient to plug monitors into the mixer than the stagebox.

![Routing XLR outputs screenshot](/images/routing/800x600/mixer_XLR_out.jpg)
