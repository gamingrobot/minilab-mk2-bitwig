# Arturia MiniLab Mk II for Bitwig in Linux

## Setup

- Download `minilab-mk2.control.js` and copy into `~/Documents/Bitwig Studio/Controller Scripts` (Windows) or `~/Bitwig\ Studio/Controller\ Scripts/` (Linux).

### Bitwig
- Connect a Minilab MkII to PC.
- Open Bitwig Studio.
- Go to `Settings -> Controller`. Controller must be added automatically.
- If not added automatically. Choose the controller by click `Settings -> Controller -> Add controller manually` then select `Arturia MiniLab mkII` or `Arturia MiniLab mkII MIDI 1` as input and output each.

### Arturia MIDI Control Center
- Open Arturia MIDI Control Center, change each knob to `Option: Relative #1`, save as preset and load onto the device memory.
- On the MiniLab, press shift and select the corresponding memory slot.

## Usage

![Layout](minilab.png)

- Pads 1 to 8 function as normal MIDI notes / drum pads.
- Pads 9 to 16 (after pressing the pad selector) function as following:
	- Pad 9 & 10 (blue) – Scroll between tracks.
	- Pad 11 – Unassigned.
	- Pad 12 (cyan) – Toggle metronome.
	- Pad 13 (cyan) – Toggle looping.
	- Pad 14 (green) – Toggle play/pause.
	- Pad 15 (yellow) – Stop playback.
	- Pad 15 (red) – Toggle recording.

- The knobs are divided vertically and function as following:
	- Knob 1 & 9 control pan and volume of the currently selected track. Click the knob to reset.
	- Knob 2, 3, 4 & 10, 11, 12 are freely assignable in Bitwig.
	- Knob 5, 6, 7, 8 & 13, 14, 15, 16 control the macros of the currently selected device.
