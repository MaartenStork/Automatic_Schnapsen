During my time at the Vrije Universiteit (VU), I worked on the practical material for the Intelligent Systems course and the Project Intelligent Systems course. These projects revolved around the card-based strategy game Schnapsen. In this project, I implemented my own bots, which are now part of the system.

For the Schnapsen game, I followed the standard rules but made a few adjustments:
	(1) Partial information about the deck state is automatically updated, so manual tracking is unnecessary.
	(2) Player and opponent points are automatically handled by the game engine. This eliminates the need to declare reaching 66 points to win.
	(3) I decided not to implement the "closing the talon" feature to clearly separate perfect and imperfect information aspects and to avoid complicating the game's branching factor.
	(4) Scoring adheres to the official rules, allowing a player to earn 1-3 points depending on the score difference. However, I focused my implementation on the rounds, rather than the full game where players play until one reaches 7 points.
