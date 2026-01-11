# Bowling Tournament Engine (Racket)

A high-complexity logic engine designed to calculate and aggregate scores for full-scale bowling tournaments. This project demonstrates advanced algorithmic thinking by translating the intricate "look-ahead" rules of bowling into a clean, functional codebase.

## Engineering Highlights

* **Recursive Scoring Logic:** Implemented the complex look-ahead rules for strikes and spares using recursive list processing, ensuring accurate frame calculation based on subsequent rolls.
* **Data Aggregation & Analytics:** Built functions to transform raw roll data into team-level totals and identify the tournament's "Most Valuable Player" (MVP).
* **Advanced Pattern Matching:** Leveraged Racket's `match` capabilities to elegantly handle various frame states (Strikes, Spares, Open Frames) and the special logic of the 10th frame.
* **Functional Integrity:** Utilizes immutable data structures to maintain a "pure" scoring environment, preventing state-related bugs often found in traditional imperative implementations.

## Tech Stack

* **Language:** Racket
* **Paradigm:** Functional Programming
* **Logic:** Recursive Pattern Matching & List Processing



---

## Installation and Usage

1. **Install Racket**:
   Download and install the Racket environment from [racket-lang.org](https://racket-lang.org/).
2. **Setup Project**:
   Clone this repository and ensure a `scores.txt` file is present in the root directory.
3. **Execute**:
   Open the main script in **DrRacket** and press **Run**, or execute via terminal:
   ```bash
   racket bowling_engine.rkt
4. **View Results**:
   The engine will output the individual scores, team totals, and the tournament winners directly to the console.
