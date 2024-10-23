---
title: Server owners
layout: default
---

# Server owners

[Work in progress]

## Valheim connection hook

Right now, the ReadyM Launcher ships with a **ReadyM Server Connection Hook** plugin enabled by default. This mod acts kind of like the [FastLink](https://thunderstore.io/c/valheim/p/Azumatt/FastLink/) mod by Azumatt, but skipping the menu; the moment the game starts it opens the character selection screen and upon selecting a character we automatically connect to the server, populating the password field (if required & provided).

However, this causes an issue with the servers that use Azumatt's [AzuAntiCheat mod](https://thunderstore.io/c/valheim/p/Azumatt/AzuAntiCheat/), as the plugin we inject is not on their greylists. Thus, we ask you to greylist the attached plugin DLL. You can inspect it with tools like ILSpy or dotPeek to verify it only does what we describe here. At the same time, we ask you for your thoughts on the following:

1. Would you be okay with greylisting this plugin? It is unlikely to change in the future, as the go-to-charater-screen functionality is pretty basic (unless Valheim devs change the main menu code again)
2. Should we upload it to Thunderstore in case you'd prefer to fetch latest versions from there?
3. Do you think the way the plugin works is good user experience for the players? If not, should we remove it altogether or perhaps switch to injecting another plugin, like **FastLink**? (though, this would still run into the anti-cheat on servers that do not allow it)

We encourage you to share your feedback with us on the [ReadyM Discord server](https://discord.gg/TTnrctVCtb).