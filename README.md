# Elova Sports — GPT Autopost Pilot

This repository is a safe pilot for preparing Elova Sports post assets. It is separate from the live `elova-sports-autopost` repository.

## Folder contract

- `images/YYYY-MM-DD-N.png` — square post artwork
- `captions/YYYY-MM-DD-N.txt` — matching caption, same date and sequence number

The live automation expects PNG files in `images/` and matching TXT files in `captions/`. This pilot does not contain or modify the live automation.

## Test asset

- Caption: `captions/2026-11-01-1.txt`
- Matching image filename reserved: `images/2026-11-01-1.png`

**Important:** the caption has been committed, but the PNG artwork could not be committed through the available GitHub file-write interface in this run (it only accepts UTF-8 text for file creation). The `images/` folder is therefore represented by `.gitkeep` until the binary PNG is uploaded.
