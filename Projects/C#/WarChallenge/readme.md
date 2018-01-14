### War Card Game
***

#### Objective

The goal of this challenge was to create a simple web page that would output the script of a simulated game of War at the click of a button. If you are not familiar with the game, the deck of cards is dealt between two players. Each round both players blindly draw a card from the top of their hand and the player with the higher value card wins the round. If the cards turn out to be tied in value it initiates a war in which each player lays their next three cards face up as a bounty prize for the war, followed by another blind draw from each player to decide the winner of the round. If another tie is drawn the wars chain together and increase the bounty until the round is won.

#### Steps Taken

This game would normally go on for quite some time as the winner of each round would take the drawn cards and add them to the bottom of their hand, playing until the winner of the game is defined by holding all the cards. For brevity’s sake, I did not follow this gameplay and instead the cards are discarded and player score incremented each round until all cards have been drawn. Aiming to practice the implementation of function-specific classes, the deck and card classes were structured such that they could potentially be reused in another card game application.

#### The Result

I really enjoyed translating the game play into the logic to be executed, even though the result doesn’t look like much. The outcome was very clean code due to the separation of classes. To accomplish such concise classes I tried to keep the amount of code for each class as close to one full-screen window as possible without the need for scrolling. This ensured that no class was responsible for more functions than necessary and reinforces the separation of concerns. Exercising this constraint enabled me to see its value in keeping code modular and reusable.

[Return to portfolio](https://github.com/zfregin/portfolio)
