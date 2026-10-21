# Noise Machine

A calming noise machine that runs entirely in your browser. You don't install anything, and none of it is a looped recording: noise, drone and scenes are generated live, so nothing repeats.

**Use it online:** https://stophyg117.github.io/noise-machine/
**Or offline:** download the repository (Code → Download ZIP), extract it, and double-click `index.html`.

## Features

- **Noise:** brown, pink or white noise, with a **tone** control (dark to bright) and **stereo width** (centred to fully independent left and right, which is good on headphones).
- **Drone:** soft, slowly evolving sine-wave notes with reverb. Four moods (Warm, Dreamy, Dark, Open) and a density control.
- **Presets:** Focus, Deep work, Calm and Wind down. Your own settings are remembered between visits.
- **Scenes:** synthesised environments, each with its own reverb and mixing sliders.
  - **Cave:** water drips from fixed spots in the ceiling, a distant trickle, shifting pebbles, cave air.
  - **Forest:** gusting wind, rustling leaves, an occasional whistle through the branches.
  - **Dock:** water lapping at the posts, small waves on the shore, creaking boards, a light breeze.
  - The drone can optionally be placed inside the scene's space.
- **Voices:** distant recorded speech placed inside the scene, in three styles: Conversation, Reading, Murmur. The recordings are public-domain LibriVox readings (see [CREDITS.txt](CREDITS.txt)).
- **Sound drops:** import your own audio clips (single files, whole folders or drag and drop) to play at random intervals. Clips are stored in your browser, play in shuffled order, and are levelled so a loud one can't blast you.
- **Timer:** fades out after 15 minutes to 4 hours.
- **Unplug guard:** stops instantly if your headphones or another audio device is disconnected.
- Space bar toggles play.

## Privacy

Everything runs locally in your browser. No accounts, no tracking, no network requests. Settings and imported clips stay in your browser's own storage.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app: page, styles and sound engine |
| `voices.js` | The recorded voices (public-domain LibriVox audio, embedded so the page also works when opened from disk) |
| `CREDITS.txt` | Sources of the recordings |
| `LICENSE` | GNU GPL v3 |

## Sound drops and copyright

The app comes with no clips. You choose what to import. Many meme and soundboard clips are excerpts from copyrighted works, so only add clips you have the right to use. Never commit them to this repository.

## License

Copyright (C) 2026 StophyG117

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. See [LICENSE](LICENSE).

In short: anyone may use, study, change and share it. If you distribute a modified version (including hosting it as a web page), you must share your changes under the same license.

The LibriVox recordings in `voices.js` are in the public domain.
