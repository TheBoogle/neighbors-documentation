[UserCFrame]: https://create.roblox.com/docs/reference/engine/enums/UserCFrame
[CFrame]: https://create.roblox.com/docs/reference/engine/datatypes/CFrame 
[Vector3]: https://create.roblox.com/docs/reference/engine/datatypes/Vector3 
[String]: https://create.roblox.com/docs/luau/strings
[nil]: https://create.roblox.com/docs/luau/nil
[Player]: https://create.roblox.com/docs/reference/engine/classes/Player

# Network Server
!!! info end "The Network server module is located in `game.ServerStorage.Modules.Network`"

A Folder inside ``ReplicatedStorage`` gets created, named "Events". These have generated UUID names...


## `:fire(`[`String`][String][`Player`][Player]`...)`
Fires an event to the specified client

### Parameters
* EventName [`String`][String]
* `...`

### Returns
* [<span style="color:Tomato"> `nil` </span>][nil]

???+ example end "Example Usage"

    ```lua
    local ServerStorage = game:GetService("ServerStorage")
    local Network = require(ServerStorage.Modules.Network)

    Network:fire("ExampleEvent", Player, "ExampleParameter", "AnotherParameter")
    ```

