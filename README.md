## The Hangman Game using React-redux:

### To run this project:
1. Clone the repo.
2. Yarn install / yarn start

### Structure of the app:
- The folder lib contains game logic. Then I created the 
- In actions folder I imported the randomWord function of the logic and exported the 2 actions (NewGame and makeGuess).
- Passed those actions to the reducers, one for the game and another for the guesses.
- The components, hangman for the total game and letters for each guess.
- One container for the componets (Board) which is passed to the App.js.

### To Do:
1. Fixing the problem when submiting a number or a letter twice.
2. Adding some nice styling
