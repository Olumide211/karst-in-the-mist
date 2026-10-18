# Karst in the Mist

An endless, procedural Li River karst sea near Guilin. It is a single `index.html` with no build step, using Three.js r160 from jsdelivr. Everything is procedural: no models, no textures.

Live: https://karst-in-the-mist-beige.vercel.app

- **Endless sea.** The world generates in chunks around you as you explore (right-drag, or drag with two fingers) and fades into mist at the horizon.
- **Wildlife.** Fish schools that scatter from the shark, leaping carp, mallard families with ducklings, water buffalo, basking turtles, herons, dragonflies and fireflies at dusk.
- **Swimmer.** A stylised game hero. Press Swimmer to walk the banks, jump (Space), wade in, swim, and dive (Shift) until your air runs out. Q surfaces.
- **Stage 1: water and mist.** Karst towers, jade water with refraction, Beer–Lambert colour, screen-space reflections and GPU ripples, mist you can part with the cursor, rain, and time of day.
- **Stage 2: raft.** A fisherman, cormorants and a bow lantern loop the channel. Click the water to send the raft there.
- **Stage 3: shark.** Press the Shark pill and swim with WASD or the arrow keys. Space bursts, Shift dives, Q surfaces, Esc exits. On touch there is a joystick plus Burst, Dive and Rise buttons.
- **Stage 4: underwater.** Dive with the shark to get jade fog, god rays, Snell's window, bubbles, and a waterline wipe when you cross the surface.

Open `index.html` through any static server, for example `npx serve .`.

Debug URL flags: `?nointro`, `?lock` (turns off adaptive quality), `?t=0.0–1.0` (time of day), `?rain`.
