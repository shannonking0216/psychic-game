# psychic-game
<!-- If you put your README file in your repository's root, docs, or 
hidden .github directory, GitHub will recognize and automatically 
surface your README to repository visitors. -->



What is Psychic Game?
    Pyschic game is a simple letter guessing game. 

How does Psychic Game work?
    1. The app has a letter in mind which the user guesses. 
    2. If the user is correct, then the user wins. This win is recorded and displayed on the screen.
    3. If the user is incorrect, the incorrect letter is recorded and displayed and the number of guesses         available to the user decreases by 1. 
    4. The user has a total of 9 letter guesses avaialble before a loss is recorded and displayed. When the       9th letter is guessed incorrectly, a loss is recorded and displayed on the screen.  
    5. Each time a win or loss is recorded and displayed on the screen, the number of guesses available to        the user is reset to 9 and the letters that have been guessed are reset to none. 
    
Who will use Psychic Game?
    Those who wish to find out if they are psychic. 

What is the goal of Psychic Game?
    Our goal is to to provide a game that is fun and interactive. 




// SHANNON"S PSEUDOCODE:
// 1. Wins & Losess start at 0; your guesses so far starts at "none"; and guesses left starts at 9.
// 2. App randomly chooses the letter "h" or "k" or "t".
// 3. User presses a key between "a" and "z". 
// 4. If user presses a key that is not the "h" or "k" or "t" key, the guesses left goes down by 1. The letter that 
//      corresponds to the incorrect key pressed by the user is then recorded and displayed in your guesses so far.
// 5. If the guesses left is equal to 1 and the user does not press the "h" or "k" or "t" key,
//      then the score for losses goes up by 1, the guesses left resets to 9, and the user 
//      letters resets to "none".
// 6. If user presses the "h" or "k" or "t" key, the score for wins goes up by 1, the guesses left resets to 9, and 
//      the Guesses so far resets to "none".
     


