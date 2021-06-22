The DudleySoft repositories are primariliy used to hold my BBC Micro projects.

Before you switch off and think 'Why would I want projects for an old 8 bit computer?', the current BBC Micro scene is generating a lot of new and exciting projects,
and since the Raspberry Pi came along it's now possible to add a 1GHz co-processor to the tube port and runs some incredible projects such as
- Frontier: Elite II
- Sierra's AGI graphic adventure games
- DOOM

and last but definitely not least
- QUAKE

I was responsible for porting three of these (I've actually done a port of all 4, but I wasn't the first DOOM port)

It also allows a lot of emulators to run on the Beeb including
- ZX81
- Jupiter Ace
- ZX Spectrum
- Amstrad CPC

and
- Gameboy

The Pi also supports virtually every co-processor ever made for the Beeb (often with speed improvements) as well as experimental new ones.

The core of my library of BBC Micro ports is my own beebScreen library, which plugs into existing games and basically replaces libSDL and allows for rapid porting
of projects to the Pi co-processor. You can find beebScreen, along with my ports on in my project repositories.
