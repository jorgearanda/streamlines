Streamlines
===========

Streamlines is a simple game for 2-4 players.  The board is a 9x9 grid
of squares.  The playing pieces are one pawn for each player, plus a
deck of cards that are the same sizes as the squares on the board.
Some of these cards have special properties, but most are streamline
cards that are marked like this:

    +-----+  +-----+  +-----+  +-----+  +-----+  +-----+  +-----+
    |  ^  |  |     |  |     |  |     |  |  ^  |  |  ^  |  |  ^  |
    |  |  |  |     |  |     |  |     |  |  |  |  |  |  |  |  |  |
    |  +  |  |<-+  |  |  +->|  |<-+->|  |<-+  |  |  +->|  |<-+->|
    |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
    +-----+  +-----+  +-----+  +-----+  +-----+  +-----+  +-----+

Each player starts in the middle of one side of the board.  On each
turn, they may move their pawn one square up, down, left, or right,
and then follow the streamlines on that square as far as they can go.
For example, if a pawn starts in square K, it could move up to square
G, then follow the streamlines and keep moving to square F, through F
to B, and into A.  It could alternatively follow the streamlines from
G through C to D.  If it started in square H, it could move to D and
follow streamlines into C, or move to G and follow strealines to F, B,
and finally A, and so on.

    +-----+-----+-----+-----+
    |A    |B    |C    |D    |
    |     |     |     |     |
    |     |<-+  |  +->|<-+  |
    |     |  |  |  |  |  |  |
    +-----+-----+-----+-----+
    |E ^  |F ^  |G ^  |H    |
    |  |  |  |  |  |  |     |
    |  +->|  +->|<-+->|     |
    |  |  |  |  |  |  |     |
    +-----+-----+-----+-----+
    |I    |J    |K    |L    |
    |     |     |     |     |
    |     |     |     |     |
    |     |     |     |     |
    +-----+-----+-----+-----+

Initially, there are no streamlines on the board.  Instead, each
player's home cell is covered by a special "Source" card.  On each
turn, a single card is added to the pile on each "Source" card on the
board.  If there are more than 3, the oldest is discarded, so that the
pile is at most 3 deep.

When a pawn is on a "Source" square, it may take some or all of the
cards from that square and carry them to empty squares on the board to
lay down. Players use this to build up networks of streamlines to
carry them from one side of the board to another more quickly.  And
yes, players can ride each others' streamlines, just as they can jump
each others' markers in Chinese checkers.

If a pawn occupies a square for its whole turn (i.e., doesn't move),
it can turn the card in that square 90 degrees in either direction to
adjust the streamlines.

If a pawn enters a square containing another pawn, the entering pawn
must stop moving (even if streamlines would allow it to keep going).
Both pawns immediately lose any cards they are carrying.

Some cards in the deck are special:

*   There are extra "Source" cards, which players can put on empty
    squares to establish forward supply bases.  Note, however, that
    anyone can take the cards that pile up there...

*   Cards marked "Only [color]" and "Not [color]"; only a pawn of the
    matching color can move onto a square of the first kind, and any
    pawn *except* the color of the second can move onto a square of the
    second kind.

*   "Pickup" cards allow a pawn to pick up the card in the square it
    currently occupies.  (The "Pickup" card is then discarded.)

*   "Poison" cards destroy a "Source".

*   "Extra Move" cards allow a pawn to move one extra square.

Cards that have been discarded go into a pile and are re-dealt when
the deck runs dry.  This means that streamline cards will eventually
be used up, and the deck will mostly contain special cards later in
the game.

If a player loses their home "Source" because a "Poison" card has been
dropped on it, they are out of the game.  The game is over when there
is only one player left alive.

Notes
-----

Should we add a rule saying streamline cards can't be opposed so that
the following wouldn't be allowed?

    +-----+-----+
    |     |     |
    |     |     |
    |  +->|<-+  |
    |  |  |  |  |
    +-----+-----+

If a pawn is on a square with a card, should it be able to remove the
card from the square and put it in the discard pile for recycling?

Should a pawn that is carrying cards have to lay down or discard one
card during each turn?
