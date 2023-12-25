# Carry
!!! info end
    ``game.ServerStorage.Modules.Tools.Carry``

## ``:Carry(plyChar: Model, targetChar: Model, carry_type, ignore)``

## Parameters
* ``carry_type``: Type of carry or ``"Default"``, see Character Attributes.
* ``ignore``: Don't check if already carrying someone. Useful for things like the _Pitchfork_.


## `:GetBullyFromCharacter(plyChar: Model)`
If a player is being carried, this function can be used on that player, to find out who is carrying them.

### Returns
The player's username that is carrying the player.


## `:GetVictimFromCharacter(plyChar: Model)`


### Returns
!!! info end
    Unsure