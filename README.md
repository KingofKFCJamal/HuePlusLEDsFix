## Hue+ LED Fix
A fix for people having trouble changing the modes/colors on their LEDs or not having access to the lighting tab for their HUE+. The file will let you change all the colors and modes if the CAM software won't let you. This has only been tested on v3.204 of CAM.

### Usage
 Drag and drop this file in your main directory of CAM and open up in your prefer text editor.
 To change a mode, go to <SelectedModeName> and change the text in between <string> </string> to your choosing.
 
### Modes
		FIXED
		BREATHING
		FADING
		MARQUEE
		COVERING MARQUEE
		PULSE
		SPECTRUM WAVE
		ALTERNATING
		CANDLE
		AUDIO
		WINGS
	
### Options
		Option | Description
------------ | -------------
`<LedGroupSize>0</LedGroupSize>` | The LED Group size when moving/selected, 0 = 3 LEDs/group - 3 = 6 LEDs/group, Default is 0
`<Speed>0</Speed>` | The speed of how fast the LEDs go, 0 = Slowest, 4 = Fastest
`<Direction>0</Direction>` | The direction of the LED's movement, 0 = Forward , 1 = Backward
`<OptionByte>0</OptionByte>` | Only applied to ALTERNATING, 0 = Not moving , 1 = Moving

