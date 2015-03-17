# Arduino Tone Library Usage #



## Instantiation ##

```

Tone notePlayer;

void setup(void)
{
  notePlayer.begin(13);
}

```


## Properties ##
  * No properties.

## Methods ##
  * <tt><a href='CommandBegin.md'>begin</a>()</tt> - prepares a pin for playing a tone.
  * <tt><a href='CommandIsPlaying.md'>isPlaying</a>()</tt> - returns <tt>true</tt> if tone is playing, <tt>false</tt> if not.
  * <tt><a href='CommandPlay.md'>play</a>()</tt> - play a tone.
  * <tt><a href='CommandStop.md'>stop</a>()</tt> - stop playing a tone.

## Constants ##

Below is a list of constant values of frequencies for notes.

e.g.

```
  notePlayer.play(NOTE_B3);
```

### Musical Notes ###
| **Constant Name** | **Frequency (Hz)** |
|:------------------|:-------------------|
<a href='Hidden comment: 
|| NOTE_B0  || 31 ||
|| NOTE_C1  || 33 ||
|| NOTE_CS1 || 35 ||
|| NOTE_D1  || 37 ||
|| NOTE_DS1 || 39 ||
|| NOTE_E1  || 41 ||
|| NOTE_F1  || 44 ||
|| NOTE_FS1 || 46 ||
|| NOTE_G1  || 49 ||
|| NOTE_GS1 || 52 ||
|| NOTE_A1  || 55 ||
|| NOTE_AS1 || 58 ||
|| NOTE_B1  || 62 ||
|| NOTE_C2  || 65 ||
|| NOTE_CS2 || 69 ||
|| NOTE_D2  || 73 ||
|| NOTE_DS2 || 78 ||
|| NOTE_E2  || 82 ||
|| NOTE_F2  || 87 ||
|| NOTE_FS2 || 93 ||
|| NOTE_G2  || 98 ||
|| NOTE_GS2 || 104 ||
|| NOTE_A2  || 110 ||
|| NOTE_AS2 || 117 ||
'></a>
| NOTE\_B2  | 123 |
| NOTE\_C3  | 131 |
| NOTE\_CS3 | 139 |
| NOTE\_D3  | 147 |
| NOTE\_DS3 | 156 |
| NOTE\_E3  | 165 |
| NOTE\_F3  | 175 |
| NOTE\_FS3 | 185 |
| NOTE\_G3  | 196 |
| NOTE\_GS3 | 208 |
| NOTE\_A3  | 220 |
| NOTE\_AS3 | 233 |
| NOTE\_B3  | 247 |
| NOTE\_C4  | 262 |
| NOTE\_CS4 | 277 |
| NOTE\_D4  | 294 |
| NOTE\_DS4 | 311 |
| NOTE\_E4  | 330 |
| NOTE\_F4  | 349 |
| NOTE\_FS4 | 370 |
| NOTE\_G4  | 392 |
| NOTE\_GS4 | 415 |
| NOTE\_A4  | 440 |
| NOTE\_AS4 | 466 |
| NOTE\_B4  | 494 |
| NOTE\_C5  | 523 |
| NOTE\_CS5 | 554 |
| NOTE\_D5  | 587 |
| NOTE\_DS5 | 622 |
| NOTE\_E5  | 659 |
| NOTE\_F5  | 698 |
| NOTE\_FS5 | 740 |
| NOTE\_G5  | 784 |
| NOTE\_GS5 | 831 |
| NOTE\_A5  | 880 |
| NOTE\_AS5 | 932 |
| NOTE\_B5  | 988 |
| NOTE\_C6  | 1047 |
| NOTE\_CS6 | 1109 |
| NOTE\_D6  | 1175 |
| NOTE\_DS6 | 1245 |
| NOTE\_E6  | 1319 |
| NOTE\_F6  | 1397 |
| NOTE\_FS6 | 1480 |
| NOTE\_G6  | 1568 |
| NOTE\_GS6 | 1661 |
| NOTE\_A6  | 1760 |
| NOTE\_AS6 | 1865 |
| NOTE\_B6  | 1976 |
| NOTE\_C7  | 2093 |
| NOTE\_CS7 | 2217 |
| NOTE\_D7  | 2349 |
| NOTE\_DS7 | 2489 |
| NOTE\_E7  | 2637 |
| NOTE\_F7  | 2794 |
| NOTE\_FS7 | 2960 |
| NOTE\_G7  | 3136 |
| NOTE\_GS7 | 3322 |
| NOTE\_A7  | 3520 |
| NOTE\_AS7 | 3729 |
| NOTE\_B7  | 3951 |
| NOTE\_C8  | 4186 |
| NOTE\_CS8 | 4435 |
| NOTE\_D8  | 4699 |
| NOTE\_DS8 | 4978 |