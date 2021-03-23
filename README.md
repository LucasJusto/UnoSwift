# UnoSwift
This repo has my first project made for command-line (terminal) in Swift. Made after studying Swift for something around 1-2 weeks.
<h2>Some features:</h2>
<p>Greetings based on the time when the player opens the game (morning, afternoon, night)</p>
<p>Cards are represented with emojis</p>
<p>Text-to-speech at 3 action cards (+4, +2, skip), to make the game funnier</p>

<h2>Uno Rules (at this implementation):</h2>
<p>The Deck to play the game has 108 cards (25 blue, 25 red, 25 yellow, 25 green, 4 wilds and 4 wild draw four). The 25 from each color are 0 + 2x[1-9] + 2 of each action cards (reverse, skip, draw two). When all the cards were already draw, the deck is reseted.<p>
  
<p>The game begins with 7 cards for each player + 1 card at the “table" to begin.<p>
  
<p>You must play a card that has the type or the color equals to the card in the table, or draw a card from the deck and forfeit your turn. At your turn you can play a wild or wild draw 4 independent of the table’s card.<p>
  
<p>Wild: choose a color to continue the game with the next player.<p>
  
<p>Wild draw 4: choose a color (like in wild) and the next player must draw 4 cards and forfeit his turn.<p>
  
<p>Reverse: simply reverse the order of playing (if the order was 1 2 3, now it is 3,2,1).<p>
  
<p>Skip: the next player must forfeit his turn.<p>
  
<p>Draw 2: the next player must draw 2 cards and forfeit his turn.<p>
  
<p>There is no limit for the amount of players.<p>
  
<p>The first player who reaches 0 cards wins!!<p>
