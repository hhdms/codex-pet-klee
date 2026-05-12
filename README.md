# Codex Pet Klee

A fan-made animated Codex pet inspired by a red clover spark-mage character design.

![Contact sheet](qa/contact-sheet.png)

## GIF Previews

GIF previews use a light checkerboard background so transparent sprite edges are easy to inspect on GitHub.

| Idle | Running Right | Running Left |
| --- | --- | --- |
| ![Idle](gifs/idle.gif) | ![Running right](gifs/running-right.gif) | ![Running left](gifs/running-left.gif) |

| Waving | Jumping | Failed |
| --- | --- | --- |
| ![Waving](gifs/waving.gif) | ![Jumping](gifs/jumping.gif) | ![Failed](gifs/failed.gif) |

| Waiting | Running | Review |
| --- | --- | --- |
| ![Waiting](gifs/waiting.gif) | ![Running](gifs/running.gif) | ![Review](gifs/review.gif) |

## Install

Download or clone this repository first:

```bash
git clone https://github.com/hhdms/codex-pet-klee.git
cd codex-pet-klee
```

### macOS

Copy the pet files into your local Codex pets directory:

```bash
mkdir -p ~/.codex/pets
cp -R pet/klee ~/.codex/pets/
```

You can also install it manually in Finder:

1. Open this repository folder.
2. Open `pet/klee`.
3. Press `Command + Shift + G` in Finder and go to `~/.codex/pets`.
4. Copy the whole `klee` folder into `~/.codex/pets`.

Restart Codex, then choose `Klee` from the pet picker.

### Windows

Copy the pet files into your local Codex pets directory with PowerShell:

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\pets"
Copy-Item "pet\klee" "$env:USERPROFILE\.codex\pets\" -Recurse -Force
```

You can also install it manually in File Explorer:

1. Open this repository folder.
2. Open `pet\klee`.
3. Open `%USERPROFILE%\.codex\pets` in File Explorer.
4. Copy the whole `klee` folder into `%USERPROFILE%\.codex\pets`.

Restart Codex, then choose `Klee` from the pet picker.

## Files

- `pet/klee/pet.json` - Codex pet manifest
- `pet/klee/spritesheet.webp` - animated pet spritesheet
- `gifs/*.gif` - per-state animated GIF previews
- `qa/contact-sheet.png` - generated QA contact sheet

## Notes

This is an unofficial fan-made asset for personal, non-commercial use. Character concepts, trademarks, and related rights belong to their respective owners.

No broad open-source license is granted for the underlying character design or IP.
