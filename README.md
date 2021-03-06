# Riley's Sound Bot

A Bot for Discord that will play various audio files.

## Required Dependencies 

1. **Node.js v6.0.0** or newer is required per [discord.js](https://discord.js.org/#!/docs/tag/master/file/general/Welcome).
  * Node-Opus should be installed with Node.js, to support voice capabilites.
2. **FFmpeg** is required, for voice capabilities.

## Commands

Type '!HelpRiley' to display the list of available commands, shown below.

```
Riley's Sound Bot v2.0

- Commands -
!HelpRiley      --- Show this message
!ListAudio      --- List all available audio files.

- Generic Audio -
!Allahu Akbar   --- Play "ALLAHU AKBAR!" sound
!TerroristsWin  --- Play CS GO "Terrorists Win" sound

- Nick Audio Expansion Pack With Bonus Kody Sound File -
!Genius         --- Play "Genius!" sound.  Audio courtesy of Nick
!ProveIt        --- Play "Prove It!" sound.  Audio courtesy of Nick
!UmmmNo         --- Play "Ummmm no?!?!?" sound.  Audio courtesy of Nick
!NotToday       --- Play "Not today!" sound.  Audio courtesy of Nick
!Now            --- Play "Now!" sound.  Audio courtesy of Nick
!Illegal        --- Play "He's an illegal" sound.  Audio courtesy of Nick
!WhoRYou        --- Play "Who are you?" sound.  Audio courtesy of Nick

- President Trump Audio Expansion Pack -
!Wrong			--- Play Donald Trump saying "Wrong".
```

## Adding New Sounds

To add a new sound, simply drop the \<filename>\.mp3 file in the ./sound folder.  The command to call the sound from Discord will simply be '!\<filename\>'.  For example, the file Allahu Akbar.mp3 is in the ./sound folder, and it is called using '!Allahu Akbar'.

## Future Features
Contact me for feature requests.
