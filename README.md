
CAN:

    1.Selects a random word from the bank for player(s).
    2.Letter guesses are checked and tells user how many times it appears in the secret word.
    3.Check Word Guesses: It allows players to guess the entire word and checks if it matches the target word.
    4.Handle Multiple Players: It prompts the user to input the number of players and initiates the game accordingly. 
    5.Incorrect WORD guesses will cause chances to go down, while letter guesses don't. Anyting above 1 letter will count as a word.
    6.Ends the game if player(s) used up all their chances. 
CANNOT:

    1. Does not tell the player what made the guess wrong.
    2. Game cannot alternate between players and instead of the players guessing for the same one they are guessing for two random words from the word bank.
    3. Same word bank, no variety of words.

RUNNING:
   
    1.Run the play game function.
    2.Enter the number of players that are playing.
    3.Each player will continue until tries are used up before moving to next player.
    4.The game will tell you if you guessed the word or a letter in the word.
    5.The game continues until all players have either guessed their word correctly or run out of chances.

CREDITS:

    1. Professor Scott - Helped me get rid of reptitive code such as the get random word function and discussed future changes that needed to be made in word guessing game.
    2. https://www.youtube.com/watch?v=M1t4RJ5XRHE - Got me started by allowing me to understand thought process and format of his word guessing game although it is not the same.
    3. https://www.youtube.com/watch?v=lRPisI6kzLg&t=57s to create the scoreboard using Pandas and Matplotlib. (The scoring is currently awkward, but does generate a graph)
    4. Idil Ibrahim - helped me a lot during pair programming by giving me advice and many different examples of tracking the remaining chances user has.
