# drum-trainer

Take a song you like, isolate the drums, and learn them in a Melodics-style trainer.

1. **Make a chart** with `tools/drumchart/drumchart.py` (Demucs stem separation + onset detection). See [tools/drumchart/README.md](tools/drumchart/README.md).
2. **Open `index.html`** (or serve this repo with GitHub Pages), load `chart.json`, and load `backing.wav` to play along.

Features: falling-note lanes, keyboard / MIDI e-kit / touch pads, Perfect/Good/Miss timing with early/late stats,
speed 40-120%, A-B loop, count-in, metronome, latency offset, and a "hear the chart" mode to check the transcription.
Audio never leaves your browser.
