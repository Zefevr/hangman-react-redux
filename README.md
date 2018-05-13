3rd Homework assigment for Codaisseur - The Hangman Game using React-redux:

First i set up the project: created the react app and installed all dependencies, added the .eslintrc file and installed redux dependencies.

I cleaned up the unnecessary code and here it came up the bigges issue (at least for me): figuering out the squeleton of my project, which components do I create, which reducers.... etc, so I made a draft drawing in a paper with the instructions on my hand and I started step by step building it up.

Created the folder lib where I put the game logic provided. Then I created the folder actions where I imported the randomWord function of the logic and exported the 2 actions as described by the instructions (newGame and makeGuess).

With the squeleton a little more clear and decided to create the reducers, here I created one for game and the other one for guesses, calling them of course for the index file of the reducers. Right after I created the components. Here is where I spent almos all my time, figuering out how to imput the letters (It is still not working as I wanted... you can put numbers and few letters at the same time "(to do list!!)"). And with the hangman component I spent a long time figuering out how to show the winner/looser, I wanted to show an alert window with that message but it didnt work as I wanted so I opted to just replace the word being guessed with the messsage once the gameFinished.

Like in the previous assigment, and as it seems good practice, I added a container for may components so everything seems more clear and organized.

I have learned a lot but I think I still need study/practice a bit more with redux, mainly about how to make the squeletong of the project etc..

I didnt spend much time on styling but this time I could add the icon of a hangman to the title-tab :)
