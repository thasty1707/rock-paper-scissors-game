# rock-paper-scissors-game
A simple webpage with script to play a game of Rock-Paper-Scissors, a.k.a. Roshambo.
Content and style are not required.
Game is against computer.
Function 1: computerPlay = to randomly return 'Rock','Paper', or 'Scissors' for the computer
Function 2: play a single round, player vs. computer, with 2 parameters, return a string to declare the winner ("You lose! Paper beats Rock!")
    Parameter 1: playerSelection
    Parameter 2: computerSelection
    Function should be case insensitive so the user doesn't worry about cap/lower case
Return the result of the function; do not console.log() them. Test with:
    function playRound(playerSelection, computerSelection) {
  // your code here!
    }

    const playerSelection = "rock";
    const computerSelection = computerPlay();
    console.log(playRound(playerSelection, computerSelection));
Then, write NEW function, game(), with prev function inside to play 5 rounds.
    Looping is optional; can simply repeat the prev function 5 times.
    Use console.log() to display the results of each round and the winner at the end.
    Use prompt() for input
    Rework prev functions if needed, esp to return a more useful value
    Create more "helper" functions if useful
