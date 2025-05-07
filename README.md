# Real-Time Typing Performance App

A responsive web-based application that allows users to practice and test their typing speed and accuracy in real-time. The application dynamically renders text paragraphs, tracks the user's performance (WPM, CPM, Mistakes), and displays real-time feedback.

## Features
- **Real-Time Metrics:** Displays Words Per Minute (WPM), Characters Per Minute (CPM), and number of mistakes.
- **Dynamic Paragraphs:** Randomly selects paragraphs for each typing session.
- **Interactive UI:** Active word highlighting and error indication during typing.
- **Reset and Retry:** Users can reset the typing test at any time to start over.
- **Keyboard Event Handling:** Smooth integration with keyboard events for seamless typing.

## Technologies Used
- **React.js** for component-based UI design.
- **JavaScript** for logic and state management.
- **CSS** for styling and responsive design.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/typing-speed-app.git
   cd typing-speed-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the application:**
   ```bash
   npm start
   ```

4. Open `http://localhost:3000` in your browser.

## Project Structure
```
📦src
 ┣ 📂components
 ┃ ┗ 📜TypingArea.js
 ┣ 📜App.js
 ┣ 📜SpeedTypingGame.js
 ┗ 📜index.js

📜SpeedTypingGame.css
📜App.css
📜index.css
```

- **App.js:** Main entry point for rendering components.
- **SpeedTypingGame.js:** Core logic for the typing game.
- **TypingArea.js:** Sub-component for displaying typing text and metrics.
- **SpeedTypingGame.css:** Stylesheet for the game UI.

## How to Play
1. Start typing the highlighted text.
2. Errors are marked in red, while correct keystrokes are marked in green.
3. Typing statistics (WPM, CPM, Mistakes) update in real-time.
4. Click 'Try Again' to restart the game.

