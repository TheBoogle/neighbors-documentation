# Utility
!!! info end
    ``game.ServerStorage.Modules.Utility``


## `:ChangeStat(instance: Instance, attrName: string, attrValue, duration)`
Utility to change Attribute values on things.

### Parameters
* ``instance``: What thing should be changed
* ``attrName``: Attribute name
* ``attrValue``: What to set the value to
* ``duration``: How long it should last. Which creates the a string that is "nameTime", "Time" gets additionally added, which tracks the time, that is in os.clock() and duration.

!!! note end
    Why... is it using os.clock()...


## `:CanPlayerUseTool(ply: Player, plyChar: Model)`
!!! info end
    Unsure

### Returns
* ``boolean``


## `:PickRandomWeighted(chances: {})`

Picks a random weighted value from a given table.

### Returns
Should return the picked **key**.

???+ example end "Example Table"

    ```lua
    local chances = {
        Good = 60,
        Bad = 40
    }
    ```