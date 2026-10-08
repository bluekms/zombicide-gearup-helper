# Zombicide: Gear Up Helper

**English** | [한국어](README.ko.md) | [日本語](README.ja.md) | [中文](README.zh.md)

A web app that shuffles and lays out the turn cards, spawn cards and boss cards for the board game *Zombicide: Gear Up*.

Use it now: https://bluekms.github.io/zombicide-gearup-helper/

## How to use

- Press a setup button at the bottom of the screen to shuffle the cards and lay them face down in 9 slots.
- Tap a card to flip it face up.
- Use the button in the top-right corner to switch between the light and dark themes. It follows your device setting at first and remembers the theme you choose.

## Phase setup

Every setup makes 9 slots and places one turn card in the top row of each slot. There are 10 turn cards, so one card is left out.

### Turn cards

| No. | Color | Symbol | Companion |
|---|---|---|---|
| 1 | Blue | x | |
| 2 | Yellow | >, >> | |
| 3 | Red | >> | |
| 4 | Green | x | |
| 5 | Red | > | |
| 6 | Green | >> | Yes |
| 7 | Green | > | |
| 8 | Blue | > | Yes |
| 9 | Red | >> | Yes |
| 10 | Blue | >> | |

### Easy 1 Phase Setup

- Top row of slots 1–9: 9 turn cards
- Bottom row of slots 3–9: 7 spawn cards (3 A, 2 B, 2 C)
- The turn card left out is always one of No. 3, 5, 7 or 10. This means the x cards (No. 1, 4), the yellow card (No. 2) and the companion cards (No. 6, 8, 9) are always placed.

### Normal 1 Phase Setup

- The slots are laid out the same as in Easy 1 Phase Setup.
- The turn card left out is a random one of the 10.

### 2 Phase Setup

- Top row of slots 1–9: 9 turn cards (the card left out is random, with no difficulty distinction)
- Bottom row of slots 3–5: 3 phase 1 boss cards
- Bottom row of slots 6–9: 4 phase 2 boss cards
- Spawn cards are not used.

## Credits

- Commissioned by: https://github.com/bluekms
- Developed by: https://github.com/nulta

Many thanks to nulta for all the hard work.
