# Karst in the Mist

An interactive WebGL miniature of the Li River karst near Guilin. It is a single `index.html` with no build step, using Three.js r160 from jsdelivr. Everything is procedural: no models, no textures.

- **Stage 1: diorama.** Karst towers, jade water with refraction, Beer–Lambert colour, screen-space reflections and GPU ripples, mist you can part with the cursor, rain, and time of day.
- **Stage 2: raft.** A fisherman, cormorants and a bow lantern loop the channel. Click the water to send the raft there.
- **Stage 3: shark.** Press the Shark pill and swim with WASD or the arrow keys. Space bursts, Shift dives, Q surfaces, Esc exits. On touch there is a joystick plus Burst, Dive and Rise buttons.
- **Stage 4: underwater.** Dive with the shark to get jade fog, god rays, Snell's window, bubbles, and a waterline wipe when you cross the surface.

Open `index.html` through any static server, for example `npx serve .`.

Debug URL flags: `?nointro`, `?lock` (turns off adaptive quality), `?t=0.0–1.0` (time of day), `?rain`.
