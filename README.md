# Card Game Suite Multiplayer

## Run locally
1. Install Node.js 18 or newer.
2. Open a terminal in this folder.
3. Run `npm install` (on Windows PowerShell, `npm.cmd install` may be needed).
4. Run `npm start` (or `npm.cmd start` on Windows PowerShell).
5. Open `http://localhost:3000`.

## Games
- Texas Hold'em
- Five-Card Draw
- Liar
- Spoons (turn-based draw/discard variant)
- Kings (house-rule card game with non-drinking rule suggestions)
- Yahtzee (five dice, three rolls per turn, standard 13 scoring categories)
- Solitaire (open the Solitaire link from the lobby)

## Room options
The room host can enable or disable betting before a game starts. This setting applies to Texas Hold'em and Five-Card Draw. When disabled, those games deal and progress without antes, bets, raises, folds, or chip payouts. The other games do not use chips.

## Multiplayer
New visitors can join the shared public room while it has fewer than six human players. Bots are disabled in the public room so its seats remain available to people. Once the public room is full, players must create a private room or enter a private room code. Private rooms support bots, with a maximum of six seats including bots. The header displays the number of connected humans on the server; bots are excluded. Rooms are stored in server memory, so restarting the server clears active rooms.

## Note
This is a casual game suite. Spoons uses a simplified turn-based variant, and Kings rules are configurable house-rule interpretations rather than a single universal ruleset.
