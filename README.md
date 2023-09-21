# Blackjack CLI Python Script

## Introduction

This is a simple command-line interface (CLI) script for playing the popular card game Blackjack. The game is also known as 21, and the objective is to beat the dealer by having a hand value as close to 21 as possible without going over. This README provides an overview of the game rules and basic strategy.

## Compatibility

This script is fully compatible with all shells and partially compatible with IDE standard output screen

## Installation

To run this Blackjack CLI script, ensure you have Python 3.x installed on your system. You can download it [here](https://www.python.org/downloads/).

1. Clone this repository to your local machine:

```bash
git clone https://github.com/muhzinkhan/blackjack.git
```

2. Navigate to the project directory:

```bash
cd blackjack
```

## How to Play

To start the game, run the following command in your terminal:

```bash
python blackjack.py
```

Follow the prompts on the screen to play the game.

## Rules

1. **Objective**: The goal of Blackjack is to have a hand value as close to 21 as possible without going over. If a player's hand value exceeds 21, they lose (bust).

2. **Card Values**:
   - Number cards (2-10) are worth their face value.
   - Face cards (Jack, Queen, King) are worth 10 points each.
   - Aces can be worth either 1 or 11 points, depending on which value benefits the hand more.

3. **Dealing**:
   - At the start, each player (including the dealer, which is the computer) is dealt two cards.
   - The dealer's first card is dealt face-up, and the second card is dealt face-down (hole card).

4. **Player's Turn**:
   - The player can choose to "hit" (take another card) or "stand" (keep the current hand).
   - Players can continue to hit as many times as they like, but if the total exceeds 21, they bust and lose the game.

5. **Dealer's Turn**:
   - After all players have completed their turns, the dealer reveals their hole card.
   - The dealer(computer) must hit until their hand total is at least 17.

6. **Winning**:
   - If the player's hand is closer to 21 than the dealer's without going over, the player wins.
   - If the player busts or the dealer's hand is closer to 21, the player loses.

7. **Blackjack**:
   - If a player is dealt an Ace and a 10-value card as their initial hand, they have a Blackjack and win immediately, unless the dealer also has a Blackjack.

## Basic Strategy

To increase your chances of winning, it's recommended to follow some basic Blackjack strategy:

- Always assume the dealer's hole card is worth 10 points.
- Hit until you have at least 12 points, then consider the dealer's face-up card.
- If the dealer has a 7 or higher showing, hit until you have 17 or more.
- If the dealer has a 4, 5, or 6 showing, stand on 12 or higher.

Please note that this is just a basic strategy and does not guarantee a win in every situation.

## Feedback and Contributions

If you have any feedback, suggestions, or would like to contribute to this project, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy gaming!