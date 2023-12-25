# Carry
!!! info end
    ``game.ServerStorage.Modules.Tools.Carry``

## ``:Carry(plyChar: Model, targetChar: Model, carry_type, ignore)``

## Parameters
* ``carry_type``: Type of carry or ``"Default"``, see Character Attributes.
* ``ignore``: Don't check if already carrying someone. Useful for things like the _Pitchfork_.


## `:GetBullyFromCharacter(plyChar: Model)`
If a player is being carried, this function can be used on that player, to find out who is carrying them, aka. who's bullying them.

### Returns
The player's character, that is carrying the player.


## `:GetVictimFromCharacter(plyChar: Model)`
If a player is carrying someone but we don't know who. We can use this function to find out who is being carried, aka. who is the victim of the carry.

### Returns
!!! info end
    The player's character that is being carried.