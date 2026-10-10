# Audio to MIDI evidence

This repository contains small, reproducible fixtures and observed MIDI event counts from browser-based audio-to-MIDI experiments. The records come from the Note Foundry workflow at https://mp3frommidi.com/ and are evidence for the documented test cases, not accuracy claims for arbitrary recordings.

## Files

- `fixtures.csv` — compact fixture table with expected and observed event counts.
- `evidence/wav-results.json` — raw WAV fixture run output.
- `evidence/mp3-results.json` — raw MP3 fixture run output.

The companion browser tool is available at https://mp3frommidi.com/. It processes supported files locally in the browser; files are not uploaded to the site. Mixed or overlapping audio can lose notes, so inspect the downloaded MIDI beside the source.

## Reproduce

The CSV and JSON records identify the generated fixtures and observed event counts. Treat each result as a controlled run record. Do not interpret it as a benchmark or an accuracy guarantee.
