# Utility
!!! info end
    ``game.ServerStorage.Modules.Utility``


## `:CanPlayerUseTool(ply: Player, plyChar: Model)`
!!! info end
    Unsure

### Returns
* ``boolean``


## `:ChangeStat(instance: Instance, attrName: string, attrValue)`
Utility to change Attribute values on things.

### Parameters
* ``instance``: What thing should be changed
* ``attrName``: Attribute name
* ``attrValue``: What to set the value to


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