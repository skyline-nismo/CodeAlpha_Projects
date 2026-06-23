# CodeAlpha_Tasks

Three independent Python command-line programs.

## Tasks

### Task 1 — Hangman Game
A command-line Hangman word-guessing game.
- The player has 6 chances to guess a hidden word, one letter at a time.
- The word is chosen at random from a fixed 10-word list built into the script.
- Per the in-game instructions, guessing an unmatched letter on the very first turn ends the round and requires a restart.

**Location:** `Task - 1 Hangman_Game/Task - 1 Hangman_Game.py`
**Dependencies:** none (Python standard library `random` only)

**Run:**
```
python "Task - 1 Hangman_Game/Task - 1 Hangman_Game.py"
```

### Task 2 — Stock Portfolio Tracker
A menu-driven command-line portfolio manager:
1. Add stocks (fetches the latest closing price via `yfinance`)
2. Display the current portfolio
3. Delete stocks from the portfolio
4. Exit

Portfolio data is held in memory only and is not saved between runs.

**Location:** `Task - 2 Stock_Portfolio_Tracker/Task - 2 Stock_Portfolio_Tracker.py`
**Dependencies:** `yfinance` (requires an internet connection to fetch live prices)

**Run:**
```
python "Task - 2 Stock_Portfolio_Tracker/Task - 2 Stock_Portfolio_Tracker.py"
```

### Task 3 — Basic Chatbot
A rule-based command-line chatbot built with `nltk.chat.util.Chat`. It matches your input against a set of regular-expression patterns and returns a randomly selected response for the matched pattern. Type `quit` to exit.

**Location:** `Task - 3 Basic_Chatbot/Task - 3 Basic_Chatbot.py`
**Dependencies:** `nltk`

**Run:**
```
python "Task - 3 Basic_Chatbot/Task - 3 Basic_Chatbot.py"
```

## Installation

```
pip install -r requirements.txt
```

Task 1 has no third-party dependencies and can be run with the standard library alone.

## Requirements
- Python 3
=======
# 