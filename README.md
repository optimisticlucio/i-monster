# Skulk

A small tabletop game I'm making to practice godot & unity later on.

## Narrative

Among the populace there live beings who do not align with what we might call “a normal human.” Cultists, lizard men, ethereal beings, and others. You are one such abnormality.
Within your vicinity, the locals have caught that something is wrong, but they can’t pinpoint what. They will find something soon, and if they don’t they’ll keep digging until they do.
You and another target have nothing personal against eachother, but it’s now whoever flees first, or is caught last.

## Summarized Rules

A 2-player deckbuilder where at the start of the game, each player picks a character that changes their starting deck and the main deck's contents. Both players seek to move the *Suspicion* meter so it favors them, and is against their opponent, eventually ending with the town uncovering the opponent's secret. To do so they'll modify and improve their deck until only one abnormality remains standing.

## Characters

- **Fly**: A person with a fly for a head. No particular goal.
- **Cultist**: Incentivized goal is to gain a specific expensive card, "Black Hole Sun", that wins the game.
- **Shapeshifter**: Incentivized goal is to play a lot of cards at once.
- **Ghost**: Incentivized goal is to remove all cards from the deck.

## Setup

1. When the game begins, each player selects a unique character card.
    1. In case both players want the same character, both players select a "backup" character (may be the same) and toss a coin to decide who gets the original choice.
2. Once the choices are made, each player gets their respective character's Baseline Deck, and add their character's Influence Deck to the Main Deck.
3. Shuffle the Main Deck and both players' baseline decks, and place the top 5 cards from the Main Deck in some place that's accessible and visible to both players; these cards are now the shop. Both players draw 5 cards from their personal decks to their hands.
4. Place the Suspicion Track in an equally visible space, and place the Suspicion Marker at 0 (the center). This marker will move towards a player if they have suspicion inflicted upon them.
5. Choose who goes first by tossing a coin or intense argument.

## Gameplay

Each player, in turn, takes their turn:

- During their turn they may play cards from their hand to their Play Area to act on whatever the card says in its card description, or purchase cards from the shop if they have enough Goodwill, or use their character-specific ability, or end their turn.
- To purchase a card a player must first have enough Goodwill, which is gained through specific cards in your deck. If you have more goodwill than a given card's cost, you place the chosen card in your discard pile, replace the removed card with the top card of the Main Deck, and reduce your current Goodwill by the card's cost.
- Each character has a unique ability listed on their character card. Each time this ability is used they inflict Suspicion on themselves, so act carefully!
- If a player chooses to end their turn, they must discard their hand and playing area into the discard pile, which is face-up and can be browsed by all players. Their Goodwill is set to 0. Afterwards, they draw 5 cards from their deck, and the other player begins their turn.
- If a player needs to draw a card from their deck, but their deck has no cards in it, shuffle the player's discard pile, place it face-down, and use it as their new deck.

If a player reaches more than 9 suspicion at any point, they lose.

If there's conflict between the rules and the card effects, follow the card effects' description.

## Keywords

- **Erase:** Remove a card from the game. It does not matter where you place it, it will not return to this match.
- **Discard:** Place a card into your discard pile.
- **Inflict [x] Suspicion:** Move the Suspicion marker [x] spaces away from you/towards your opponent.
