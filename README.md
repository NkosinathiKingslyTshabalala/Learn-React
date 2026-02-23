# Tic-Tac-Toe Game - React Tutorial Learning Project

This project is a Tic-Tac-Toe game built by following the official React tutorial. It demonstrates fundamental React concepts through a practical, interactive application.

## Project Overview

A fully functional Tic-Tac-Toe game with features including:
- Interactive game board with clickable squares
- Turn-based gameplay (X goes first, then O)
- Winner detection and display
- Game history tracking with navigation to any previous move
- Status display showing current player or winner

## Core React Concepts Learned

### Components
- Created reusable components (Square, Board, Game)
- Learned component naming conventions (capital first letter)
- Understood component composition and nesting

### Props
- Passed data from parent to child components
- Customized component behavior through props
- Experienced prop drilling and learned to lift state up

### State Management with useState
- Managed component-level state
- Understood state updates trigger re-renders
- Learned immutability principles (using .slice() instead of direct mutation)

### Event Handling
- Added onClick handlers to interactive elements
- Passed event handlers as props
- Used arrow functions to prevent infinite re-renders

### Lifting State Up
- Moved shared state to common parent components
- Enabled communication between sibling components
- Improved application data flow

### Immutability
- Understood why immutability enables features like time travel
- Created array copies instead of mutating original data

### Conditional Rendering
- Displayed different UI based on game state
- Used ternary operators and if statements in JSX

### Lists and Keys
- Rendered lists of components with .map()
- Understood key importance for React's reconciliation process
- Implemented proper keys for list items

### Time Travel
- Stored game history as an array of board states
- Implemented navigation between past moves
- Used immutability to enable undo/redo functionality

## Technical Challenges Addressed

- Fixed infinite loop bug by understanding function call timing in renders
- Determined optimal state location (component vs parent)
- Resolved key prop warnings for rendered lists

## Key Takeaways

- React applications are built from components, props, and state
- Designing component hierarchy and data flow should precede implementation
- Immutability ensures predictable state management
- Lifting state up enables data sharing between components
- Developer tools help debug component state and props

## Potential Improvements

- Show current move indicator instead of button
- Rewrite Board with loops instead of hardcoded squares
- Add toggle for ascending/descending move history
- Highlight winning squares
- Display move coordinates

This tutorial provides a foundation for building more complex React applications.
