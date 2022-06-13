# lottery-daml-app
A lottery model that attempts to keep the organiser of a draw from knowing about the numbers that bets have been placed on and use that information for their advantage.

# templates
- Book
    * Simple naive bookkeeping for the control of transfer for balances for the placing of bets and the transfer of winnings.
- Draw
    * A lottery draw.
- Ticket
    * Ticket for a draw.
    * Contains refence to set of `Numbers` and their matching bets.
- Numbers
    * Encapuslation for a set of 7 numbers rannging from 1 to 49.
