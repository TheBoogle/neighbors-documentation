[UserCFrame]: https://create.roblox.com/docs/reference/engine/enums/UserCFrame
[CFrame]: https://create.roblox.com/docs/reference/engine/datatypes/CFrame 

# Server


## `:GetUserCFrame(` [`UserCFrame`][UserCFrame] `) → `[`CFrame`][CFrame]

!!! danger end "Internal"
    This function should not be used.

Returns the controller [`CFrame`][CFrame]. 

### Parameters
* [`UserCFrame`][UserCFrame]

### Returns
* [`CFrame`][CFrame]

???+ example end
    ```lua
    local ServerStorage = game:GetService("ServerStorage")
    local ServerVRModule = require(ServerStorage.Modules.VR)

    local USerCFrame = ServerVRModule:GetUserCFrame(Enum.UserCFrame.Head)
    ```