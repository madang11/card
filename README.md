# Card

 Card.java
 <code>Card</code> represents a playing card.

	 * String value that holds the suit of the card
	 * String value that holds the rank of the card
	 * int value that holds the point value.

Creates a new <code>Card</code> instance.
	 * @param cardRank  a <code>String</code> value
	 *                  containing the rank of the card
	 * @param cardSuit  a <code>String</code> value
	 *                  containing the suit of the card
	 * @param cardPointValue an <code>int</code> value
	 *                  containing the point value of the card

Accesses this <code>Card's</code> suit.
	 * @return this <code>Card's</code> suit.

Accesses this <code>Card's</code> rank.
	 * @return this <code>Card's</code> rank.

Accesses this <code>Card's</code> point value.
	 * @return this <code>Card's</code> point value.
	

Compare this card with the argument.
	 * @param otherCard the other card to compare to this
	 * @return true if the rank, suit, and point value of this card
	 *              are equal to those of the argument;
	 *         false otherwise.

public boolean matches(Card otherCard) {
/* *** TO BE IMPLEMENTED IN ACTIVITY 1 *** */
}


Converts the rank, suit, and point value into a string in the format
    "[Rank] of [Suit] (point value = [PointValue])".
This provides a useful way of printing the contents
of a <code>Deck</code> in an easily readable format or performing
other similar functions.
	 * @return a <code>String</code> containing the rank, suit,
	 *         and point value of the card.

@Override
public String toString() {
/* *** TO BE IMPLEMENTED IN ACTIVITY 1 *** */
}

