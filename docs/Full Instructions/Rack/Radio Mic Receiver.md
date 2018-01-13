# Radio Mic Receiver

The radio mic receiver is a Sennheiser EW100 G3 used with the handheld radio mic (Sennheiser SKM 100-835 G3), which lives on the shelf with the other mics.

It is plugged into `input 3` on the back of the rack mixer, which internally routed to `aux 4`.

The radio mic uses `RF`, which is radio frequency to transmit `AF`, which is audio frequency - the actual sound signal. Both terms are used throughout this guide.

## Antennas

The receiver uses two antennas, and switches between then based on which has the highest signal level.

This switching can be seen on the left of the screen, where the `I` and `II` levels are displayed, labeled `RF`. The antenna currently being used is highlighted. Their audio levels, labeled `AF` are displayed just to the right.

Antenna I is plugged directly into the back of the receiver. _If there are reception issues, an extension cable can be used to put this antenna behind the left-hand TV._

Antenna II is behind the right-hand TV, on an extension cable.

## Tuning

1. Press `set`
2. Press `▼` to find `Frequency Preset`
3. Press `set`
4. Press `▲` and `▼` to choose a legal preset with a low `RF` signal _(see below)_
5. Press `set`
6. Press `▼` to find `Exit`
7. Press `set`
8. Press the `Sync` button the the left of the screen. The mic has a little window to the right of the screen. Hold this close to the window on the receiver to transfer settings by magic.

When scrolling through frequencies, the received level is displayed on the `AF` graphs. With our mic off, this should be very low - if it isn't, it's likely there is someone else using the frequency, which may lead to interference. Try to choose one with the lowest background level possible.

If frequencies can't be found with no background level, there are two steps that will help stop interference:

- Leave the mic on, this should overpower the other signal
- Increase the squelch

## Squelch

The squelch is basically a gate on the `RF` signal. It mutes the `AF` until it reaches a certain level.

This is mostly used to mute the pilot tone that the mic sends to let the receiver know it's still there, but can also be used to keep down interference from other radio mics tuned to the same frequency.

The squelch level is displayed as a dotted line at the bottom of the `RF` graphs.

This shouldn't need adjusting - refer to the manual if it does.

## Further Reading

- [User manual](https://en-uk.sennheiser.com/global-downloads/file/8939/EM_100_G3_Manual_12_2016_EN.pdf) explains everything in more detail
- [Frequency charts](https://en-uk.sennheiser.com/global-downloads/file/3073/Radio_Mic_Frequency_charts_2014.pdf) explains which frequencies are legal to use.

