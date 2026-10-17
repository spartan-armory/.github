<h1 align="center">Spartan Armory</h1>

<p align="center">Tools for Halo Infinite players, built with a Halo HUD look.</p>

---

## The tools

| | What it is | Status |
| --- | --- | --- |
| <img src="halo-labs.png" alt="" width="20" height="20"> **[Halo Labs](https://halolabs.gg/)** | The home of the tools, at [halolabs.gg](https://halolabs.gg/): a dashboard with accounts, a HUD look in a choice of palettes, and docs for every page. | Live |
| **Halo Stats** | Read from Halo Infinite itself. A player's ranked CSR with Halo's own rank emblems, career and combat figures over any window, best maps and modes, and every ranked match with both teams' scoreboards and medals. Plus **Pro Stats** for the LVT Halo Pro League and **Teams**, pro and community. Part of Halo Labs. | Live |
| **[Halo Tracker](https://halolabs.gg/tracker/download)** | A Windows overlay on top of Halo Infinite that reads the kill feed (OCR) to show who on each team is alive, dead or respawning. After each match it checks its own count against Halo's scoreboard, and sends the match to Halo Labs. | Live, 1.1 |

## Built with

- **Halo Labs**: React, TanStack Router, Tailwind; a small Node API on SQLite; accounts linked to Xbox, with email sign-in codes. Halo Stats reads Halo Infinite's own services through a linked Xbox account.
- **Halo Tracker**: C# on Windows' built-in OCR, drawn as a transparent, click-through overlay. It only reads the screen: no memory reading, no input automation, nothing hooked into the game.

---

<sub>Spartan Armory is a fan project. Halo is a trademark of Microsoft; this project isn't affiliated with or endorsed by Microsoft or Halo Studios. Halo Labs is made under Microsoft's Game Content Usage Rules.</sub>
