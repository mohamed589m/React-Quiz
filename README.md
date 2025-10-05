# React Quiz App

A modern, interactive quiz application built with React to test your knowledge on JavaScript and React fundamentals.

## Features

- **Timed Quiz**: Each question has a 30-second timer to keep you engaged.
- **Progress Tracking**: Visual progress bar showing your current position in the quiz.
- **Scoring System**: Earn points for correct answers, with varying point values per question.
- **Highscore**: Track your best performance across sessions.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.
- **Local Data**: Questions stored in a JSON file, served via JSON Server.

## Technologies Used

- **React**: Frontend library for building the user interface.
- **JavaScript (ES6+)**: Programming language.
- **CSS**: Styling for the application.
- **JSON Server**: Mock API for serving quiz questions.
- **Create React App**: Build tool for React applications.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/react-quiz-app.git
   cd react-quiz-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the JSON Server for questions:
   ```bash
   npm run server
   ```
   This will start the server on http://localhost:8000

4. In a new terminal, start the React app:
   ```bash
   npm start
   ```
   The app will open at http://localhost:3000

## Usage

1. Click "Let's start" to begin the quiz.
2. Answer each multiple-choice question within the time limit.
3. Click "Next" to proceed to the next question.
4. View your final score and highscore at the end.
5. Click "Restart quiz" to try again.

## API

The app fetches questions from a local JSON Server running on port 8000.

Endpoint: `GET /questions`

Response format:
```json
{
  "questions": [
    {
      "question": "Question text",
      "options": ["Option 1", "Option 2", "Option 3", "Option 4"],
      "correctOption": 0,
      "points": 10
    }
  ]
}
```

## Demo

[Live Demo Video](https://github.com/user-attachments/assets/b54e51da-6dc7-431f-8769-4928bd5a387b)



