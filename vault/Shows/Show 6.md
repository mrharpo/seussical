---
date: 2025-11-14
start: 2025-11-14T19:00:00
---

## About
Family here
## Times

| Event           | time  |
| --------------- | ----- |
| Mic check start | 15:50 |
| Mic check stop  | 16:00 |
| House open      |       |
| Curtain speech  | 19:05 |
| Act I           | 19:09 |
| Intermission    | 20:09 |
| House flash     | 20:24 |
| Act II          | 20:26 |
| End             | 21:18 |

## Notes
- [x] Add v19 to QLab
- [x] Check elephant horn
	- Dante audio cut out from QLab computer for about 10s
	- Happened right when the cue was pressed
	- Nothing else weird about that moment, no sound dropped out in house
---
## Preflight

- [x] Open Tech booth
- [x] Open Equipment room
- [x] Crestron
	- [x] Start
	- [x] Advanced mode
	- [x] Video
		- [x] PC -> Projector
		- [x] Camera -> BOH 1
		- [x] Camera -> BOH 2
		- [x] Camera -> Lobby
	- [x] Volume
		- [x] Mute lobby
	- [x] Settings
		- [x] Screen up
- [x] 2nd Crestron
	- [x] House out
	- [x] Fixture power: on
	- [x] Work lights: off
- [x] Sound
	- [x] Start sound board
	- [x] Load showfile
	- [x] Turn on front fills
	- [x] Verify front fill levels at 12:00
- [x] Lights
	- [x] Start light board
	- [x] Load showfile
	- [x] goto cue `0.1`
	- [x] Verify lights onstage respond
- [x] VFX
	- [x] Start VFX projector
	- [x] Connect HDMI
	- [x] Load VFX QLab
	- [x] Verify projection on stage
	- [x] Start caffiene app
- [x] Primary computer
	- [x] Start computer
	- [x] TheatreMix
		- [x] Load TheatreMix showfile
		- [x] Connect TheatreMix to Sound board
		- [x] Load cue `0`
		- [x] Verify soundboard channels changed to actor names
		- [x] Load cue `0.1`
		- [x] Verify Main channel strip reads `0.1`
	- [x] Ardour
		- [x] Start Ardour
		- [x] Create new from `Seussical` template
	- [x] QLab
		- [x] Load QLab showfile
		- [x] Preflight cue list
			- [x] `a0` Verify sound plays through speakers
			- [x] `s0` Verify TheatreMix responds
			- [x] `0.1` Verify lighting console responds
			- [x] `x1` Verify VFX responds
			- [x] `r0.1` Verify recording starts
			- [x] `r0.2` Verify recording stops
- [x] Mics
	- [x] Get mics from tech closet
	- [x] Add batteries to all mics
	- [x] Turn on all mics
	- [x] Check battery levels
	- [x] Distribute mics to actors
	- [x] Sound check
---
## House open
- [x] goto `0.1` House open
- [x] Crestron
	- [x] unmute lobby
## Curtain speech
- [x] Booth lights out
---
## Intermission
- [x] Booth lights up
- [x] Flash house
	- [x] Flash lobby
- [x] Booth lights down
---
## Postflight
- [x] VFX
	- [x] Turn off projector
	- [x] Shut down VFX computer
- [x] Sound
	- [x] Turn off sound board
	- [x] Turn off monitors
	- [x] Turn off front fills
- [x] QLab
	- [x] Shut down QLab computer
- [x] Mics
	- [x] Get mics from actors
	- [x] Remove batteries from all mics
	- [x] Return mics to equipment room
- [x] Lights
	- [x] Turn off lighting console
	- [x] Cover lighting console
- [x] Crestron 2
	- [x] House lights full
	- [x] Works on
- [x] Crestron 1
	- [x] Power off
- [x] Lock Equipment room
- [x] Lock Tech booth
