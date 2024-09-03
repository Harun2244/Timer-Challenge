
React Timer Challenge Application
This project is a simple React application that presents a series of timer challenges to the user. The user can start and stop timers for different challenges, and their results are shown in a modal dialog. The application demonstrates the use of React refs and portals.

Features
Timer Challenges: Users can start and stop timers with different target times.
Player Name: Users can set their player name, which will be displayed throughout the challenges.
Result Modals: After stopping the timer or when the time runs out, a modal dialog shows the user's score or indicates if they lost.
Key Concepts
This project focuses on the following key React concepts:

Refs (useRef): Used for directly accessing and manipulating DOM elements (e.g., controlling the timer and modal).
Portals (createPortal): Used to render the modal dialog outside of the usual DOM hierarchy, enabling it to appear above other content.
Project Structure
The application consists of the following components:

App.jsx

The main component that renders the Player component and a list of TimerChallenge components.
Player.jsx

Manages the player's name input and displays a welcome message with the entered name.
TimerChallenge.jsx

Handles the timer logic for each challenge and interacts with the ResultModal to display the outcome.
ResultModal.jsx

A modal dialog component rendered via a portal. It displays the result of a timer challenge and includes a reset functionality.
