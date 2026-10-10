# Swarm Rush — Game Design Map

An interactive map of the full game design for Swarm Rush, a co-op auto-survival roguelite I am designing for Roblox. Pan, zoom, and click through every system, from classes and skills to gear, the match loop, and the economy, with a detailed breakdown for each one.

**[View the live map](https://swarm-rush-map.vercel.app)**

## About

I built this as a living design document. Instead of a long text file, the whole game plan is a map you can explore: a central hub branches out into the major systems, and each node opens a panel with its mechanics, numbers, and notes. You can also add, edit, and delete nodes right in the browser, and your changes save automatically.

## Features

- Interactive radial map: pan, zoom, drag, and click any node
- A detail panel for every system, with mechanics, stats, and dev notes
- Add, edit, and delete nodes directly in the browser
- Saves your changes locally with localStorage
- Works on desktop and touch, with pinch to zoom

## Built with

- HTML, CSS, and JavaScript (no framework, single file)
- SVG for the connecting lines
- localStorage for saving

## Run it

It is a single HTML file, so you can open `index.html` directly in your browser. To serve the folder instead:

```
python -m http.server
```

Then open `http://localhost:8000`.

## About the game

Swarm Rush is a Survivor.io style auto-survival roguelite I am designing for Roblox: survive an endless swarm, collect XP, level up, and build each run from a roster of skills, collectible classes, and a gear system. Co-op is a core part of the design.

## License

See the `LICENSE` file in this repository.

---

Built by Oleksandr Rybitskyi.
GitHub: [@vitamindgoat](https://github.com/vitamindgoat) · Hugging Face: [@vitamindgoat](https://huggingface.co/vitamindgoat)
