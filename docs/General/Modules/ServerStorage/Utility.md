# Utility
!!! info end
    ``game.ServerStorage.Modules.Utility``


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