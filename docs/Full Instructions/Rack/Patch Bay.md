# Patch Bay

The patch bay is used to connect the etherCon sockets on the walls into the equipment in the rack. The short patch cables in the front are used to connect two sockets on the patch bay to one-another.

It also features two connections into the IT network, allowing for internet access.

When the patch bay is understood, it can be used very flexibly, as any pieces of equipment can be connected accross the room.

## etherCon

All the wall and patch sockets use etherCon connectors.

These are ruggedised RJ45 connectors, that are build more like an XLR. They can withstand much more abuse, and their latches don't fall off.

Note, however that a regular RJ45 conenctor will also fit in so, in a pinch, a ethernet patch cable can be used instead of an etherCon cable.

One of our cables has an etherCon on one end, and regular RJ45 on the other. This is solely for the use of the HDMI-cat5 converter.

## Equipment Connections

These live on the left-hand side of the bottom row.

- **X32 Stagebox** Connects to the rack mixer's `AES 50 A` connection, usually used for the stagebox
- **X32 Mixer** Connects to the rack mixer's `AES 50 B` connection, usually used for the main mixing console
- **X32 Network** Connects to the rack mixer's `Network` connection, allowing for remote access to the rack mixer for tablets and the like
- _[Pinter pause](https://en.wikipedia.org/wiki/Characteristics_of_Harold_Pinter%27s_work#The_%22Pinter_Pause%22)_
- **Video** The cat5 input of the cat5 to HDMI converter, that leads onto the screens

## IT Network connections

These live on the middle of the bottom row.

_The network setup is still a work-in-progress, so may not work._

If wall sockets have been patched to the network, please un-patch them when finished, to avoid miscreants gainging access to the rack mixer, or worse, through the wall sockets.

- **Network CC1** The first conenction into the IT network. _Usually patched to **X32 Network**
- **Network CC2** The second connection into the IT network. _This currently doesn't seem to work._

## Wall Sockets

The live on the top row, except the `Cafe`, which is on the bottom right.

Any wall socket can be used for anything, not just what they're labelled with, as it's just a straight bit of cat6 cable. However it's usually best to stick to the labels to avoid confusion.

There are five locations with wall sockets in:

- **Front** In the middle of the wall with the TVs on, usually used as the stage area.
- **Left** Next to the main door, near the large window. This is often the most convenient place for Front of House (FOH).
- **Rear** In the middle of the rear wall (opposite the front wall).
- **Right** In between the storage cupboard and kitchen.
- **Cafe** Behind the cafe-style tables. A convenient place to put a mixer and/or projection laptop, but be aware it's not great acoustically.

Each location has four etherCon sockets, labelled with their location and function.:

- **[location] Stagebox** Intended for the stagebox to plug into.
- **[location] Mixer** Intended for the main mixing console to plug into.
- **[location] Video** Intended for the HMDI-cat5 converter for the projection or speaker's laptop to plug into.
- **[location] Spare** Can be used for anything else such as a backup if another conenction fails. It can also be used to conenct a device into the network, for instance, to allow remote access to the main mixer.

## Behind the Rack

The back of the patch bay has a lot of cat5 cables coming out from the patch bay. These are all labeled to match the front of the patch bay.

The short blue cables go straight to other equipment in the rack.

The longer beige cables (not our colour choice) go in a big bundle to the sockets on the wall. Which are also labelled.

## Connection Recipes

The following are some example ways to use the patch bay.

### Normal setup for events using the Main Mixer

- `X32 Stagebox` to `Front Stagebox`
- `X32 Mixer` to `Left Mixer`
- `Video` to `Cafe Video` (could be left video to suit laptop position)

### Normal Setup for Band Practice using Mixer

- `X32 Stagebox` to `Front Stagebox`
- `X32 Mixer` to `Front Mixer`
- `Video` to `Front Video` (to put chords on the screen)

### Normal Setup for Band Practice using Remote App

- `X32 Stagebox` to `Front Stagebox`
- `X32 Network` to `Network CC1`
- `Video` to `Front Video` (to put chords on the screen)

### Using Main Mixer with Remote App

Assumes mixer is in cafe

- `X32 Mixer` to `Cafe Mixer`
- `Network CC1` to `Cafe Spare` (with cable plugged into mixer's network socket).

### Using a Second Mixer for Monitors

Assumes FOH is at rear, and monitors desk (FB) to the left.

This needs some routing set up - this is left as an excercise for the reader.

_This is unlikely to be a sensible setup for any event in The Living Room, as using a tablet for monitors is probably a better idea. It's shown mainly to demonstrate the flexibility of the patch bay._

- `X32 Stagebox` to `Front Stagebox`
- `X32 Mixer` to `Rear Mixer`
- `Rear Spare` to `Left Mixer` The FOH mixer's `AES 50 B` is plugged into `Rear Spare` on the wall. The FB mixer's `AES 50 A` is plugged into `Left Mixer`
