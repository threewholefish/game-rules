# UnoGoRummy

Version 1.0

An amalgamation of Uno, Go Fish and (gin) Rummy

"Go fish is structured and ordered: you ask for a card or draw a card. You build your hand, hoping to get a set (or a run for rummy). Rummy is balanced, allowing you to draw, place down sets and runs you have built up, and discard. And Uno is just pure chaos, throwing down special cards to fuck everyone over."

## Requirements
* An Uno deck of your choice

## Rules
* The objective of the game is to be the first player to have no cards remaining in their hand
* Each player is dealt five cards. The player to the left of the dealer goes first, and play proceeds clockwise
* The game alternates between Uno, Go Fish and Rummy, with the first player playing Uno, the next playing Go Fish, and so on.
    * The draw and discard piles are used for all games, so a discard from an Uno round may be picked up as part of the Rummy round
* If, during an Uno round, a special card is played, then the effects of that card immediately apply
    * For instance, a skip card means the next player is skipped, and the next after that will play Go Fish
    * If a +2 or +4 is played, the next player must pick up that number of cards, unless they can chain, in which case the following player has the same opportunity. Once a player has picked up cards at the end of the chain, the following player will play Go Fish
    * If a special card is discarded during a non-Uno round, its effects do not apply.
* If, at the beginning of an Uno round, the player has one card remaining and has not previously said "Uno" in relation to said card, they must say "Uno" as quickly as possible after the Rummy round's discard, whereafter the standard Uno pickup rules shall apply
* For the purposes of making runs in Rummy, the order of precedence of the cards in ascending order is as follows:
    * 0-9
    * Reverse
    * Skip (🚫)
    * +2
    * Wild
    * +4
    * Blank
* For the same purposes, Wild, +4, and Blank cards can belong to a run of any colour/suit
