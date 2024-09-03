# Bulls and Cows - A Number Guessing Game (on RUST)
## Overview
Bulls and Cows is an engaging and straightforward command-line game built in Rust. The objective is to guess a randomly generated number between 1 and 10. With each guess, the game provides feedback, helping you inch closer to the correct number. The challenge is to guess the number in as few attempts as possible, with hints provided after multiple incorrect tries.

## Features

•🎲 Random Number Generation: Every game session generates a new random number, ensuring a unique experience each time you play.

•✅ Input Validation: The game checks your input to ensure it's a valid number within the specified range.

•💬 Interactive Feedback: After each guess, you'll receive feedback on whether your guess was too low, too high, or correct.


## Getting Started

### Prerequisites

Rust and Cargo: Ensure you have Rust installed on your machine.

### Installation

#### 1.Clone the Repository
```
git clone https://github.com/yourusername/bulls-and-cows.git
cd bulls-and-cows
```
#### 2.Build the Project
```
cargo build --release
```
#### 3.Run the Game
```
cargo run --release
```
## How to Play

1.Start the game by running the command `cargo run --release`.

2.You will be prompted to guess a number between 1 and 10.

3.Enter your guess and receive feedback instantly.

4.Continue guessing until you find the correct number. 

5.Celebrate when you successfully guess the number!

## Example Gameplay
```
BULLS AND COWS!!!!

Please input a number:
> 3
Too small!

Please input a number:
> 7
Too large!

Please input a number:
> 5
Congratulations! You guessed the correct number in 3 attempts!
```
## Contributing

Contributions are welcome! If you'd like to improve the game or add new features, feel free to fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
