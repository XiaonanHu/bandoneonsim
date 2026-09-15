# Bandoneon Simulator

A free, browser-based bandoneon practice tool. Load a MusicXML score and it
shows you which buttons to press on a 142-button (Rheinische Tonlage)
bandoneon, plays the music with a bandoneon-like sound, and follows along in
the engraved sheet music.

**Live site:** https://bandoneonsim.com

## Features

- Load `.musicxml`, `.xml`, or `.mxl` (compressed) scores — everything runs in
  your browser; your files are never uploaded anywhere
- Both keyboards drawn in standard chart orientation with note names on every
  button, separate open (⊓) and close (⊔) pitches
- Engraved sheet music with a playback cursor; click any note to jump there
- Bellows control: set open/close per measure by hand, get a suggestion, let
  the app choose automatically, or alternate every measure for practice
- Notes that aren't playable in the current bellows direction still sound and
  are flagged, with the alternative button marked
- Tempo control, per-measure looping, chord symbols, repeats and endings

## Usage

Open the site, drop a MusicXML file on the page, press Space or Play.
Staff 1 is the right hand, staff 2 the left hand.

The whole app is a single `index.html` — you can also download it and open it
offline.

## Credits

- Button layout data: Dave Ludlow / Ignacio Irigaray,
  [Bandoneon MuseScore plugin](https://github.com/IgnacioIrigaray/Bandoneon_Plugin_MuseScore);
  cross-checked against [nicokaiser/bandoneon](https://github.com/nicokaiser/bandoneon) (MIT)
- Sound: FluidR3 GM tango accordion samples via
  [gleitz/midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts) (MIT)
- Sheet rendering: [OpenSheetMusicDisplay](https://opensheetmusicdisplay.org/) (BSD-3-Clause)
- Inspired by the xmlplay tool at [bandochords.de](https://bandochords.de/)
