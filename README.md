# Shrexplorer
What is shrex? 

Shrex is an explorer than can be run with a script executor or dropped into a game for debugging reasons. This doesn't require custom functions for the explorer to load, but the remotespy, properties tab, and script viewer won't work.
Because the remotespy is modular, you can just pass every remote through the ui module if you really want it to work in your game. If you want the properties tab to work, just replace the httpget with a remotefunction that returns the API dump in JSON form.

[UI Preview](https://cdn.discordapp.com/attachments/758387480410980434/1164399534261141564/image.png)

[VT scan of the RBXM file](https://www.virustotal.com/gui/file/3fc7e1e6ba44fd779bd88f7c8884dcaff8b8916a45c28aa3d3192de09463d1c3)

# Credits
Here's a list of every tool, resource, and individual that helped me make this.

Shrex Credits:

[Latte Softworks: Maui](https://github.com/latte-soft/maui) for compiling the explorer into a single script that only requires one httpget (api dump)
[Moon:](https://v3rmillion.net/member.php?action=profile&uid=47) [LARPing](https://v3rmillion.net/showthread.php?tid=1175699)
[Boatbomber: Textlabel syntax highlighter](https://github.com/boatbomber/Highlighter)
[MaximumADHD: Api Dump](https://github.com/MaximumADHD/Roblox-Client-Tracker/blob/roblox/API-Dump.json)
[Roblox Docs: DeepCopy](https://create.roblox.com/docs/luau/tables)
[domboss37: Draggable gui](https://devforum.roblox.com/t/how-to-make-a-draggable-gui-object/2090579)

ShrimpleSpy Credits:

[ImmuneLion318: Lua implementation of hookmetamethod and argguard](https://v3rmillion.net/member.php?action=profile&uid=1404692)
[Boatbomber: Textlabel syntax highlighter](https://github.com/boatbomber/Highlighter)
[ComoEsteban: Converttable](https://v3rmillion.net/showthread.php?tid=1152646)
[domboss37: Draggable gui](https://devforum.roblox.com/t/how-to-make-a-draggable-gui-object/2090579)
