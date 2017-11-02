# Main Mixer Default Setup

The `default` scene sets the mixer up to a basic, unopionated, state, from which a new show can be created.

Sensible defaults are selected, and the common aux channels set up, but most input channels are left for the user to set up themselves.

## Channel Strip setup

A very minimal setup is performed on the channel strips:

- Gates, compressors and EQ are turned on, but left unset otherwise.
- Channels are centre-panned, with the mono/centre level set to -18dB, which gives an even spread from left-to-right.
- The exception is channels pre-configured as stereo, which are panned 60% L/R respectively, which ensures some of the signal comes through the front fill.
- Channels 17-24 are set up for the common aux inputs - more information below.
- Four commonly used effects are set up - more information below.

## Channels 17-24

The aux channels are set up for you out of the box.

- **17 & 18** _Kitchen L&R_ The bluetooth/CD player in the kitchen.
- **19 & 20** _PC L&R_ The audio coming from the computer, via the bluestream box.
- **21** _Wireless Mic_ The handheld radio mic.
- **22** _Backup Mic_ A backup mic, in case the radio mic fails - this should be plugged into channel 16 on the stagebox.
- **23 & 24** _AuxIn 5/L&6/R_ The Aux In jacks on the back of the mixer.

All these channels go through DCA 6, called `playback`.

All these channels are in mute group 6.

![Channels 17-24 layout](/images/mixer/800x600/aux_channels.jpg)

## Effects

A selection of effects are set up. They take their input from their respective busses, and their outputs come back throught the `Effects Returns` faders.

- **Bus 13** _Room_ A fairly short reverb
- **Bus 14** _Hall_ A longer reverb
- **Bus 15** _Delay_ An echo-like effect
- **Bus 16** _Chorus_ A more subtle effect for thickening out.

All these effects go through DCA 7, called `effects`

All these channels are in mute group 5.

![Effects layout](/images/mixer/800x600/fx_channels.jpg)
