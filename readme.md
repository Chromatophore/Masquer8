# Masquer8
Masquer8 is another submission for Octo-ber jam II: http://octojam.com/octojam-ii/games/masquer8
It's written for Octo, a high-level assembler for Chip 8, an 8 bit assembly language from the 1970s: https://github.com/JohnEarnest/Octo

Masquer8 is a game where you control Cammy Cuttlefish, a master of disguise.

!! Using V on the main menu will continue from the last level you were on !!

Blend in with your surroundings perfectly so that the Shark can't see you!

You start with access to Vertical Lines on keys 1-4. Every time you change your pattern, the shark will get slightly closer. There is an icon for it in the bottom right corner. If you can see its eyes, it's really close!

At any time, press V to try and blend in. If you're not quite a perfect match, you will lose a lot of time and the shark will get closer. You must be lined up both horizontally and vertically. This can be very hard with some patterns.

After a few levels you will unlock horizontal lines on keys Q-R.

You will then unlock Patterns mode, which is REALLY HARD, on keys A-F and Z to C. A pro tip to get started is that, remember these puzzles are only 2 or 3 layered patterns, so, find one you think must be involved and try toggling on other patterns.

If you get a game over, press V on the title screen (or just navigate all menus with V) to Continue from the level you were on.

The game has 10 levels.

After you get the ending screen, you will enter infinite mode, where you will be presented with random puzzles to match. In this mode, the Shark will ignore you. If you can't beat a puzzle, or get your camouflage in a muddle, mash V a bunch and it will give you a game over and allow you get a new puzzle.

You can press Z on the title screen to jump straight to infinite mode, also.

Infinite mode is really, really hard, and I often see a puzzle on it and go 'how the hell can you do that??', so, don't feel bad.

The game was designed to be playable even at 7 cycles / frame. It also has a loading screen where it generates all of the patterns for Cammy, instead of having to program them in yourself. This means that there's about 1.5K of 0s at the end of the code, which hopefully would have been easier to type in. Unfortunately, it uses rather too much memory to have been genuinely playable on original hardware, but with some small design alterations it may have been possible to play this in the 70s.