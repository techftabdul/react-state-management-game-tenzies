#Tenzies – React State Management Game

Tenzies is a simple dice game built in React.

#The goal: Roll dice until all dice show the same number. Players can “hold” dice to lock their value while rerolling the others.

While the game looks simple, the project focuses on React fundamentals, including:

Managing arrays of objects in state

Conditional rendering

Child-to-parent communication via callback functions

Derived state vs side effects

Immutable updates for complex state

#This project is part of my React learning journey and helped solidify the mental model for real-world React applications.

#Demo:

You can play the game locally after cloning the repo.

#Features

Roll dice

Hold dice to prevent rerolling

Conditional styling: Held dice turn green

Detect when the game is won

Button changes text to “New Game” when the game is completed

Reset the game with a single click

Technologies

React (Functional Components & Hooks)

nanoid (Unique ID for each die)

CSS / Tailwind for styling

Getting Started
Prerequisites

Node.js & npm installed

Installation
git clone <repo-url>
cd tenzies
npm install
npm run dev # or npm start depending on setup

Open the browser at http://localhost:5173 (or the port Vite shows).

What I Learned

This project was simple in concept but powerful for React practice. I strengthened my skills in:

Thinking declaratively rather than imperatively

Updating nested/array state immutably using .map()

Using callback props to communicate from child → parent

Conditional rendering and styling

Derived state computation (gameWon) without unnecessary useEffect

This foundation makes me confident to build real-world React applications next.
