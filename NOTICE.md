# NOTICE

herdr-zed-vesper — Copyright 2026 Vasudev Jaiswal

This project contains modified copies of files from the Herdr app, licensed
under the Apache License, Version 2.0 (see `LICENSE`):

- `mods/zed-tabs/` from the Herdr "tabs" mod (0.1.12), via
  [herdr-zed](https://github.com/nsudhanva/herdr-zed) (Apache-2.0).
  Changes: flat tab bar (no tab pill or bar border), a Zed button, `zed.js`,
  bundled fonts, Windows launch fallbacks and Windows path handling.
- `mods/zed-pane/` from the Herdr "pane" mod (0.1.13).
  Changes: the header's bottom border is removed; home-folder abbreviation
  handles Windows `\` separators.
- `mods/zed-status/` from the Herdr "workspace-status" mod (0.1.13).
  Change: the top border is removed.
- `layouts/herdr-zed-vesper.json` from the Herdr "main" layout (0.1.12), via
  herdr-zed. Changes: Vesper theme, Lilex and IBM Plex Sans, flat pane frame,
  and the `zed-tabs`, `zed-pane` and `zed-status` mods.
- `layouts/herdr-zed-vesper.svg` is original art drawn for this layout.

`themes/vesper.json` is a Herdr theme built from the Vesper palette by
Rauno Freiberg (<https://github.com/raunofreiberg/vesper>), using the palette
from the Zed port by bdsqqq (<https://github.com/bdsqqq/vesper-zed>).

Fonts in `mods/zed-tabs/fonts/`:

- Lilex, Copyright 2022 Mikhael Khrustik, SIL Open Font License 1.1
  (`LICENSE-Lilex.txt`).
- IBM Plex Sans, Copyright IBM Corp., SIL Open Font License 1.1
  (`LICENSE-IBMPlexSans.txt`).
