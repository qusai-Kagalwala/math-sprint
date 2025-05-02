# ⏱️ MathSprint

🧮 A fun command-line math quiz game that tests your calculation speed!

## 📖 Description

MathSprint is a simple yet engaging command-line math quiz game designed to improve your mental calculation skills. Challenge yourself to solve 10 arithmetic problems as quickly as possible while tracking your time and accuracy.

## ✨ Features

- 🧮 Random arithmetic problems (addition, subtraction, multiplication)
- ⏱️ Times your performance from start to finish
- 🔄 Immediate feedback on incorrect answers
- 📊 Performance tracking (total time, wrong attempts, final score)
- 🎯 Customizable difficulty through min/max operand values

## 🚀 Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/mathsprint.git
   cd mathsprint
   ```

2. Run the game:
   ```
   python timed_quiz_game.py
   ```

## 🎮 How to Play

1. Press Enter to start the quiz
2. Solve each arithmetic problem as quickly as possible
3. Enter your answer and press Enter
4. If your answer is incorrect, you'll be prompted to try again
5. After completing all 10 problems, you'll see your total time, number of wrong attempts, and final score

## 📝 Example

```
Press Enter to start the quiz...
-- Start of the quiz --
Problem #1: 8 + 5 = 13
Problem #2: 7 * 10 = 70
Problem #3: 12 - 4 = 8
...
-- End of the quiz --
Nice work! You finished the quiz in 42.68 seconds!
Wrong attempts: 2
Your score is 80 %
```

## 🛠️ Customization

You can modify the following constants in the code to adjust the game difficulty:

- `OPERATORS`: Available arithmetic operations
- `MIN_OPERANDS`: Minimum value for operands
- `MAX_OPERANDS`: Maximum value for operands
- `TOTAL_PROBLEMS`: Number of problems in the quiz

## 📊 Scoring

Your score is calculated as: (Number of problems - Wrong attempts) * 10%

A perfect score is 100% (no wrong attempts).

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:

1. Report bugs and issues
2. Suggest new features or improvements
3. Submit pull requests

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Thanks to all math enthusiasts who enjoy mental calculation challenges
- Inspired by traditional math drills and speed tests
