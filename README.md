# Night Shift

**A FNAF 2-inspired browser survival game**

---

## About

You're a security guard at Freddy Fazbear's Pizza, and your job is simple: survive from 12 AM to 6 AM. Do that six nights in a row and you're golden. The animatronics, however, have other plans.

Built as a single HTML file — no install, no framework, just open it in a browser and try not to die.

---

## How to Play

- **Survive** from 12 AM to 6 AM each night
- **Power** is limited — every action costs power. Hit 0% and it's lights out
- **The Puppet** escapes if the music box timer reaches 0 — instant game over, no exceptions
- Clear all 6 nights to win

---

## Controls

| Key | Action |
|-----|--------|
| `Q` | Flashlight (scares animatronics in the Left Hall) |
| `E` | Toggle Mask (fools most animatronics) |
| `1` | Camera: Left Hall |
| `2` | Camera: Main Stage |
| `3` | Camera: Vent / Prize Corner |
| `Space` | Wind Music Box |

---

## Your Tools

- **Flashlight** — scares most animatronics back a step. Can't use while wearing the mask.
- **Mask** — fools animatronics that respond to it. Blocks your flashlight and music box while active.
- **Cameras** — check where the animatronics are. Some are camera-shy and retreat when spotted.
- **Music Box** — keeps The Puppet locked away. Wind it constantly. Seriously.

---

## The Animatronics

| Animatronic | Night | Flashlight | Mask | Notes |
|---|---|---|---|---|
| Toy Freddy | 1 | ✅ | ✅ | |
| Toy Bonnie | 1 | ✅ | ✅ | |
| Toy Chica | 1 | ✅ | ✅ | Camera-shy — retreats when spotted |
| Balloon Boy | 1 | ✅ | ❌ | Disables your flashlight for 20s |
| Foxy | 1 | ✅ | ❌ | Ignores the mask entirely |
| The Puppet | 1 | ❌ | ❌ | Wind the music box — there is no other defense |
| Mangle | 2 | ❌ | ✅ | Aggression spikes if the vent goes unwatched 15s+ |
| Withered Bonnie | 2 | ✅ | ✅ | More aggressive than the Toy version |
| Withered Chica | 2 | ✅ | ✅ | Camera-shy, very aggressive |
| Withered Freddy | 2 | ✅ | ✅ | Highest aggression in the building |

---

## Night Progression

Each night the building gets worse. Passive power drain increases, action costs go up, and more animatronics become active. By Night 6, every wasted second costs you. Prioritize the music box, use the mask efficiently, and don't flashlight unless you have to.

---

## Tech

- Single HTML file — open and play, no setup required
- Firebase Realtime Database for the leaderboard (optional — works without it)
