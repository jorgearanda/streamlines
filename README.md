Streamlines
===========

Streamlines is a cooperative game for 2-4 players.  The board is a 9x9
grid of squares.  The playing pieces are one pawn for each player,
plus a deck of cards that are the same sizes as the squares on the
board.  Some of these cards have special properties, but most are
square streamline cards that are marked like this:

    +-----+  +-----+  +-----+  +-----+
    |  ^  |  |     |  |  ^  |  |  ^  |
    |  |  |  |     |  |  |  |  |  |  |
    |  +  |  |<-+->|  |<-+  |  |<-+->|
    |     |  |     |  |     |  |     |
    +-----+  +-----+  +-----+  +-----+

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

But note: a pawn *cannot* enter a square moving against a streamline.
This means that a pawn cannot enter square F from square B or G, and
that the only way for a pawn to enter square G is from square K.

Initially, there are no streamlines on the board.  Instead, the four
home squares are each covered by a special "Source" card.  On each
turn, a single card is added to the pile on each "Source" card on the
board.

When a pawn is on a "Source" square, it may take some or all of the
cards from that square and carry them to empty squares on the board to
lay down. Players use this to build up networks of streamlines to
carry them from one side of the board to another more quickly.
However, a pawn *must* shed one of the cards it is carrying each turn.

If a pawn occupies a square for its whole turn (i.e., doesn't move),
it can turn the card in that square 90 degrees in either direction to
adjust the streamlines.

Some cards in the deck are special:

*   There are extra "Source" cards, which players can put on empty
    squares to establish forward supply bases.

*   Cards marked "Only [color]" and "Not [color]"; only a pawn of the
    matching color can move onto a square of the first kind, and any
    pawn *except* the color of the second can move onto a square of the
    second kind.

*   "Pickup" cards allow a pawn to pick up the card in the square it
    currently occupies.  (The "Pickup" card is then discarded.)

*   "Extra Move" cards allow a pawn to move one extra square.

*   "Gate" squares allow pawns to jump to matching "Gate" squares as
    part of their move.  (But only matching gates: there are several
    different symbols on "Gate" cards.)

Cards that have been discarded go into a pile and are re-dealt when
the deck runs dry.  This means that streamline cards will eventually
be used up, and the deck will mostly contain special cards later in
the game.

Victory
-------

OK, so how *do* the players win?
