# Gridlock Royale

A 25-car, top-down 3D car-combat battle royale that runs in a phone browser.

**Play:** https://roundmango.github.io/gridlock-royale/

- **Last car standing wins.** Everyone gets one respawn. Lose both lives and you're out.
- **The storm** shrinks the island in six phases and burns anyone caught outside.
- **Wanted stars** climb with mayhem. One star brings cruisers, three brings SWAT and a chopper, five brings army tanks and a gunship. Lose the heat at a RESPRAY garage, with a bribe, or by hiding.
- **30 weapons** come from crates. Grab the same one again to upgrade it to LV3. Airdrops carry an orbital laser, an airstrike and a tactical nuke.
- **7 rides**, each with its own special: nitro ram, mine dump, ground pound, cloak, freeze nova, soul siphon, and a frame job that pins your stars on someone else.

## Multiplayer

One player taps **HOST GAME** and shares the 4-letter code. Friends tap **JOIN GAME** and enter it. Bots fill every empty seat up to 25. The host's device runs the match, so the host should keep the game open in the foreground.

Connections are browser-to-browser (WebRTC via the public PeerJS signaling server). Most home and office networks work. Some strict mobile carrier networks block direct connections; switching one player to Wi-Fi usually fixes it.

## Controls

- **Touch:** drag anywhere on the left half to drive toward your thumb. FIRE, MG, BOOST and SPECIAL are on the right. Tap a weapon square to switch weapons.
- **Keyboard:** arrows or WASD to drive, Space fire, F machine guns, Shift boost, E special, Q or Tab to switch weapon, C handbrake, M map, Esc pause.

Built with three.js. Everything else (city generation, physics, AI, netcode, audio) is in `index.html`.
