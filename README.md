Streamlines
===========

Streamlines is a cooperative game for 2-4 players.  The board is a 9x9
grid of squares that represents a remote corner of the galaxy.  The
playing pieces are one ship for each player, plus a deck of cards that
are the same sizes as the squares on the board.  There are four kinds
of cards:

- Power cards: give the players abilities
- Streamline cards: help control movement
- Refugee cards: represent the people the players are trying to rescue
- Event cards: good or bad news (usually bad)

The game also includes two other kinds of cards,
which are arranged on the board
according to the map of the scenario the players choose to play.
These are Escape tile cards, and Planet tile cards.

The goal of the game is rescue as many Refugees as possible before
disaster overwhelms the playing board.  To rescue Refugees, a player
must carry them on a ship from a Planet square (where they first
appear) to an Escape square (where they leave).  The players win if
they save at least as many Refugees as required in their scenario
before the planets are consumed by black holes.

Powers
------

At the start of the game, each player is given one Action card, one
Cargo card (Action and Cargo cards are two kinds of Power cards), 
and two other Power cards dealt at random.

* Action: each ship gets one action per turn for each Action card it
  has.
* Cargo: each ship can carry one Refugee or one Streamline card for
  each Cargo card it has.

Unless specified, Power cards are not discarded after being used.

Unused Power cards are shuffled into the shared deck to be dealt out during
the game.

Turns
-----

Players take turns to play, in clockwise order.
A player's turn consists of two phases: a Clock Is Ticking phase and an Actions phase.

During the Clock Is Ticking phase, the player draws one card per Planet.
For each card drawn, if it is a Collapse card, follow the rules on the
Events -> Collapse section. Otherwise, discard the card.

When one card per planet has been drawn, the player moves to the Actions phase.

Actions
-------

In each turn, each ship can perform as many actions as it has Action
cards.  Allowed actions are:

* Make one move.
* Pick up one card when on an Planet square.
* Play a Streamline card on an empty square.
* Drop off refugees at an Escape square.
* Transfer one unit of cargo to another ship on the same square.

Movement and Streamlines
------------------------

Streamline cards are marked like this:

    +-----+  +-----+  +-----+  +-----+
    |  ^  |  |     |  |  ^  |  |  ^  |
    |  |  |  |     |  |  |  |  |  |  |
    |  +  |  |<-+->|  |<-+  |  |<-+->|
    |     |  |     |  |     |  |     |
    +-----+  +-----+  +-----+  +-----+

As one action, a ship may move one square up, down, left, or right,
and then follow the streamlines from that square as far as they can
go.  For example, if a ship starts in square K below, it could move up
to square G, then follow the streamlines and keep moving to square F,
through F to B, and into A.  It could alternatively follow the
streamlines from G through C to D.  If it started in square H, it
could move to D and follow streamlines into C, or move to G and follow
strealines to F, B, and finally A, and so on.

    +-----+-----+-----+-----+
    |A    |B    |C    |D    |
    |     |     |     |     |
    |     |<-+  |  +->|<-+  |
    |     |     |     |     |
    +-----+-----+-----+-----+
    |E ^  |F ^  |G ^  |H    |
    |  |  |  |  |  |  |     |
    |  +->|<-+  |<-+->|     |
    |     |     |     |     |
    +-----+-----+-----+-----+
    |I    |J    |K    |L    |
    |     |     |     |     |
    |     |     |     |     |
    |     |     |     |     |
    +-----+-----+-----+-----+

However, a ship can never enter a square moving against a streamline
(not even at the start of its movement).  This means that a ship
cannot enter square F from square B or E, and that the only way for a
ship to enter square G is from square K.

Loading Up
----------

Initially, there are no streamlines on the board.  Instead, whenever a
ship is on a Planet square, it may use an Action to draw one card from the deck.
This card may be a:

* Power card: the player adds it to the ship's capabilities and
  may draw another card (without using up additional Actions).
  If subsequent cards are also Power cards, the player may continue drawing
  (without using up Actions). 
* Refugee or Streamline cards: these fill up the ship's cargo carrying
  capacity. If there is no cargo space in the ship to accommodate the new card,
  the player must get rid of (dump into space) 
  one of their cards in cargo or the card that was just drawn.
  Refugee cards dumped this way are lost for the rest of the game.
  Streamline cards dumped this way are placed in the discard pile,
  and so they may come back to the game later on.
* Event cards: these take effect immediately. The player may then draw another card
  (without using up additional Actions).
  If subsequent cards are also Event cards, the player may continue drawing
  (without using up Actions). 

Events
------

Events are:

* Collapse: the first Collapse card is merely a warning.
  Place it on top of the Planet it was drawn from.
  The second Collapse card indicates that the planet is about to turn
  into a black hole.
  Every player, including the player who drew the Collapse card,
  has one more turn before the Planet's star turns into a black hole.
  When it turns into a black hole, the Planet is no longer a source of tiles,
  and any ship sitting on or passing through the black hole is lost forever.
  The game ends, and all players lose,
  when all of the Planets have been turned into black holes. 
  Alternatively, the
  players win if they have rescued the required number of refugees
  before that happens.
  Additional Collapse cards on a collapsing planet have no effect
  and are discarded.

Special Cards
-------------

Some cards in the deck are special:

* Pickup: allows a ship to pick up the Streamline card in the square
  it currently occupies, *if* it has cargo capacity to hold it.  The
  "Pickup" card is then discarded.
* Extra Move: gives a ship one extra move (and is then discarded).
* Gate: ships can jump to the matching Gate square as part of their
  movement, but must then immediately stop (i.e., they can follow
  streamlines to a gate, but not from it in the same turn).  Ships may
  only jump between matching Gates, and Gates must be carried into
  place like other cargo.
* Engineering: allows a ship that uses it when on top of a Streamline
  card to rotate that Streamline card 90 degrees in either direction.
  The Engineering card is then discarded.

Cards that have been played go into a pile and are re-dealt when the
deck runs dry.  This means that streamline cards will eventually be
used up, and the deck will mostly contain special cards later in the
game.
