# Party
!!! info end
    ``game.ServerStorage.Modules.Party``

A Module that does most of the Party system.


## ``:IsPlayerLeader(ply: Player)``
Whether the player is the party leader.
### Returns
* ``boolean``


## ``:ChangePartyLeader(currentLeader: Player, newLeader: Player)``
Changes the Party Leader. This also changes the ``PartyId`` attribute.<br>
The ``PartyId`` is a Player's UserId.


## ``:GetPartySize(partyId)``
Gets the party size...
### Returns
* ``number``

## ``:DoesPlayerBelongToParty(ply: Player)``
If the Player has not PartyId attribute, it would return ``false``.
### Returns
* ``boolean``