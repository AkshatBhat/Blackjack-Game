# Blackjack Game

A command-line Blackjack experience where you take on an automated dealer while managing a chip stack across multiple hands. The project ships with both a Python script and a matching Jupyter notebook.

## Features
- Standard 52-card deck with shuffling before every hand.
- Chip betting ledger that persists until you quit or lose your bankroll.
- Dynamic Ace adjustment that automatically switches from 11 to 1 to avoid busting.
- Dealer AI that follows casino rules: hits until reaching 17 or more, then stands.
- Clear terminal prompts for betting, hitting, and standing decisions.

## Project Files
- `MilestoneProject2.py` — standalone script ready to run from the command line.
- `MilestoneProject2.ipynb` — notebook version for interactive exploration or debugging.

## Requirements
- Python 3.7 or newer.
- No external packages; everything relies on the standard library.

## How to Run
1. Open a terminal in the `Blackjack-Game` directory.
2. Launch the script:
   ```bash
   python3 MilestoneProject2.py
   ```
3. Enter your starting chip total, place a bet for the round, and choose whether to hit (`h`) or stand (`s`) when prompted.

To walk through the logic cell by cell, open the notebook in Jupyter with:
```bash
jupyter notebook MilestoneProject2.ipynb
```

## Gameplay Notes
- Blackjack (21 on your opening two cards) wins immediately.
- If you bust, your bet is lost; if the dealer busts, you win that round.
- Bets settle after every hand, and your updated chip total is displayed. The game ends automatically if you hit zero chips or when you choose to quit.

Enjoy the game, and may the cards treat you kindly!
