# Routing

## AES50

The `X32` uses `AES50` for its audio network. Although intimidating at fist, the concepts involved are actually fairly simple, and allow fairly creative routing to be achieved.

`AES50` is a 48x48 bus, meaning it carries 48 mono channels in each direction (in and out).

The mixers have two AES50 ports, labled `AES50 A` and `AES50 B`.

Each device chooses 48 channels to write onto each AES output. On the X32, these are assigned in blocks of 8. These are freely choosable from:

- The device's internal processing's outputs
- The device's local XLRs
- The device's local Aux inputs, with choice of monitor mix or talkback mic
- Other AES50 inputs/outputs
- Card/USB inputs outputs

The device on the other end receives these channels as its AES inputs, and can then assign them to its internal processing channels.

Stagebox | AES50 | Rack Mixer | AES50 | Main Mixer
---------|-------|------------|-------|-----------
➡️ | Stagebox inputs | ➡️ | Stagebox inputs | ➡️
➡️ |                 | ➡️ | Rack mixer local inputs | ➡️
⬅️ | Monitor outpus  | ⬅️ | Mix outputs | ⬅️
⬅️ |                 | ⬅️ | Monitor outputs | ⬅️

## Internal Processing

The channel processing block connects the inputs, from AES50, local inputs and more, to the processing channels of the mixer.

These channels can be taken from the following:

- The device's internal processing's outputs
- The device's local XLRs
- The device's local Aux inputs, with choice of monitor mix or talkback mic
- Other AES50 inputs/outputs
- Card/USB inputs outputs
