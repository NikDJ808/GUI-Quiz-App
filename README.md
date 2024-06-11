# Quizzler App

Quizzler is a Python-based quiz application that allows users to test their knowledge on various topics. The app presents questions and tracks the user's score, providing a fun and interactive way to learn.

## Features

- Interactive quiz interface
- Multiple choice questions
- Score tracking
- Feedback on correct/incorrect answers

## Screenshots

![True](images/true.png)
![False](images/false.png)

## Installation

To run the Quizzler App locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/quizzler-app.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd quizzler-app
   ```
3. **Install the required dependencies:**
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the main application script to start the quiz:

```bash
python main.py
```

## Project Structure

- `data.py`: Handles the data for the quiz questions.
- `main.py`: The main entry point for the application.
- `question_model.py`: Defines the `Question` class, representing each quiz question.
- `quiz_brain.py`: Contains the logic for the quiz, including checking answers and tracking the score.
- `ui.py`: Manages the user interface for the quiz.
- `images/`: Contains images used in the app.
