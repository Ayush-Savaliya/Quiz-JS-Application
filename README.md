# JavaScript Quiz App

## Project Overview

This is a dynamic and interactive quiz application built using HTML, CSS, and JavaScript. It allows users to customize their quiz experience by selecting various quiz settings such as the number of questions, category, type (multiple-choice, true/false), and difficulty level. The quiz fetches questions from an API and provides users with real-time feedback, scoring, and a final results screen.

## Features

- **Screen 1 - Quiz Options:**
  - Allows the user to customize the quiz settings (number of questions, category, type, and difficulty level).
  - Includes a "Start Quiz" button to proceed to the quiz questions.

- **Screen 2 - Quiz Questions:**
  - Displays the quiz questions fetched from the Open Trivia Database (API).
  - Provides multiple-choice or true/false options for each question.
  - Allows navigation between questions using the "Next Question" button.
  - Shows a "Quit Quiz" button to end the quiz early and view the final score.
  - Real-time scoring: marks correct answers in green, incorrect answers in red, and displays the correct answer when wrong.
  - Displays the user's total score as they progress through the quiz.

- **Screen 3 - Quiz Results:**
  - Displays the user's final score after completing the quiz.
  - Includes a "Play New Quiz" button to restart the quiz with new settings.

## Technologies Used

- **HTML**: Structure of the web pages.
- **CSS**: Styling for the quiz screens and user interface.
- **JavaScript**: Logic for fetching quiz questions, scoring, and handling user interactions.
- **Open Trivia Database API**: Provides the quiz questions.

## Installation Instructions

1. Clone the repository:
 ```bash
  git clone https://github.com/Ayush-Savaliya/Quiz-JS-Application.git
   ```
2. Navigate to the project folder:
 ```bash
   cd Quiz-JS-Application
   ```
3. Open the `index.html` file in your browser to run the app.

## Usage

1. **Start Quiz:**
- On the first screen, customize the quiz settings (number of questions, category, type, and difficulty).
- Click "Start Quiz" to proceed to the next screen.

2. **Answer Questions:**
- Read the question and select one of the available options.
- After answering, click "Next Question" to move to the next question, or click "Quit Quiz" to end the quiz early and view your score.

3. **View Results:**
- After completing all the questions or quitting early, you will be shown your final score.
- You can restart the quiz with new settings by clicking the "Play New Quiz" button.

## API Used

The quiz fetches questions from the **Open Trivia Database API**. The API allows you to retrieve questions based on selected categories, difficulty levels, and types. More information about the API can be found here: [Open Trivia Database](https://opentdb.com/api_config.php)

## Development Setup

To start development or contribute to the project, follow these steps:

1. **Clone the repository:**
 ```bash
    git clone https://github.com/Ayush-Savaliya/Quiz-JS-Application.git
   ```

2. **Install Dependencies:**
- This project does not require any external dependencies as it only uses vanilla HTML, CSS, and JavaScript.

3. **Run the app locally:**
- Open the `index.html` file in your browser.

## Contribution

If you'd like to contribute to the project, feel free to submit a pull request. Please ensure your changes do not break the app's functionality.

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them with a descriptive message.
4. Push your changes to your forked repository.
5. Submit a pull request.


### How to Deploy on GitHub Pages

1. Navigate to your project folder in the terminal.
2. Ensure the `index.html` file is in the root directory of your project.
3. Add, commit, and push your changes to GitHub.
```bash
git add .
git commit -m "Completed JavaScript Quiz App"
git push origin main
  ```

4. Go to your GitHub repository.
5. Under the "Settings" tab, scroll to "GitHub Pages" section.
6. Set the source branch to main and click "Save."
7. After deployment, the green success message will show a link to your live project.
