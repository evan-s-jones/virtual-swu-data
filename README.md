# Virtual SWU: card index

Static card index for the Virtual SWU Tabletop Simulator mod.

- `sets.json`: every set code, name, card count and file path
- `cards/<SET>.json`: card entries keyed `SET_NNN` (name, type, image URLs, landscape and double-sided flags)
- `overrides.json`: manual patches applied when the index is built

The index is generated from the [swu-db.com](https://swu-db.com) API. It contains card names and links
to images only; no card art is stored here. Star Wars: Unlimited card names and images are the property
of Fantasy Flight Games and Lucasfilm. This is an unofficial fan project, not affiliated with or
endorsed by them.

Published from the `data/` folder of the main project with `git subtree push`. Do not edit here directly.
