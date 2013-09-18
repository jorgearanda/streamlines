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

The goal of the game is rescue as many Refugees as possible before
disaster overwhelms the playing board.  To rescue Refugees, a player
must carry them on a ship from a Planet square (where they first
appear) to an Escape square (where they leave).  The players win if
they save more than half of the Refugees before the planets are
consumed by black holes.

Powers
------

At the start of the game, each player is given one Movement card, one
Cargo, and two other Power cards dealt at random.

* Action: each ship gets one action per turn for each Action card it
  has.
* Cargo: each ship can carry one Refugee or one Streamline card for
  each Cargo card it has.

Unused Power cards are put in the shared deck to be dealt out during
the game.

Actions
-------

In each turn, each ship can perform as many actions as it has Action
cards.  Allowed actions are:

* Make one move.
* Pick up a card when on an Planet square.
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
    |  +->|  +->|<-+->|     |
    |     |     |     |     |
    +-----+-----+-----+-----+
    |I    |J    |K    |L    |
    |     |     |     |     |
    |     |     |     |     |
    |     |     |     |     |
    +-----+-----+-----+-----+

However, a ship can never enter a square moving against a streamline
(not even at the start of its movement).  This means that a ship
cannot enter square F from square B or G, and that the only way for a
ship to enter square G is from square K.

Loading Up
----------

Initially, there are no streamlines on the board.  Instead, whenever a
ship is on a Planet square, it draws one or more cards from the deck.
These cards may be:

* Power cards: the player adds them to the ship's capabilities and
  keeps drawing.
* Refugee or Streamline cards: these fill up the ship's cargo carrying
  capacity.  The player stops drawing cards when it is full.
* Event cards: these take effect immediately.

If a ship occupies a square for its whole turn (i.e., doesn't move),
it can turn the card in that square 90 degrees in either direction to
adjust the streamlines.

Events
------

Events are:

* Collapse: when a collapse card appears, it is stacked on the Planet
  it is drawn at.  When there are three Collapse cards on a planet,
  its star collapses, turning it into a black hole.  The game ends
  when all of the Planets have been turned into black holes.  The
  players win if they have rescued more than half of the refugees
  before that happens.

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

Cards that have been played go into a pile and are re-dealt when the
deck runs dry.  This means that streamline cards will eventually be
used up, and the deck will mostly contain special cards later in the
game.
