# Prompt
!!! info end
    ``game.ServerStorage.Modules.Prompt``

This Module uses a Network event named ``Prompt``.

All of the prompts might just be purple though...

## ``:Prompt(ply: Player, title, msg, duration, autoshow: boolean)``
Sends one of those prompts at the top of someone's screen.

### Returns
* Result from ``Network:invoke`` which triggers a RemoteFunction.