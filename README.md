 # 💻Project: Number Guessing Game
##What's this all about?

Welcome to the Number Guessing Game, a fun little project I put together as part of the FreeCodeCamp Relational Databases Beta Certificate course.
##How does it work?

So, picture this: I created a cool database in PostgreSQL where I stash all your info and game history. There are a couple of tables - 'Games', where I keep track of your game history, like how many guesses you made and what the secret number was, and 'Players', where I remember your username and ID so I know if you're a new or returning player.

Then there's this slick Bash script that runs the game right here in your terminal. It's pretty neat - keeps going until you crack the code and find the secret number. And hey, if you're stuck, it'll give you hints whether your guess is too high or too low.

Plus, I'm always on the lookout for new players. Whenever someone new shows up, I make sure to update the database. And you know what's really cool? I keep track of your game history, so even if you've played before, I'll remember your past games.