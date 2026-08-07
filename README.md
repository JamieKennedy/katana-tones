# Katana Tones

A personal, Markdown-first collection of tones created for the **BOSS Katana-100 Gen 3**. These guides document the amp, EQ, effect, and playing settings behind each tone so they can be browsed, recreated in BOSS Tone Studio, adapted to different rigs, or used as a starting point for something new.

This repository intentionally contains written guides rather than downloadable liveset files.

## Browse the tones

| Collection | Description |
| --- | --- |
| [Artists and songs](tones/artists/) | Personal interpretations of tones associated with particular artists or songs. |
| [General tones](tones/general/) | Reusable sounds organised by style, gain level, texture, or purpose. |

Tone guides are added as their settings are documented and refined.

## Compatibility

The settings are authored on a **BOSS Katana-100 Gen 3** using BOSS Tone Studio for Katana Gen 3. Other Katana models may offer compatible controls, but effect availability, parameter ranges, signal routing, speakers, and results can differ.

Treat every guide as a repeatable starting point rather than a promise of an identical sound. Guitar construction, pickups, strings, tuning, playing dynamics, room acoustics, output method, and listening volume all affect the result.

## How to use a guide

1. Open BOSS Tone Studio for Katana Gen 3 and create a new tone setting.
2. Copy the amplifier, EQ, signal-chain, and listed effect values from the guide.
3. Use the recommended pickup, tuning, controls, and playing guidance where practical.
4. Set the master volume and Power Control for your environment.
5. Use the guide's adjustment notes to compensate for your guitar, speaker position, room, and volume.

Values are written using the labels and scales shown in BOSS Tone Studio. Unused disabled effects are omitted. An effect appears as **Off** only when it is stored that way for activation during a named song section; the guide notes when to switch it on. Master volume and other system-level settings are recorded as context because they are not necessarily stored as part of a tone setting.

For the complete effect definitions and parameter ranges, see the official [BOSS Tone Studio for Katana Gen 3 guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf).

## Repository conventions

- Artist and song guides live at `tones/artists/<artist>/<song>.md`.
- General guides live at `tones/general/<tone-name>.md`.
- Folder and file names use lowercase kebab-case; headings preserve the correct display names.
- New guides start from [`templates/tone-guide.md`](templates/tone-guide.md).
- The relevant collection index is updated whenever a guide is added.
- Guides use generic pickup guidance and do not identify a contributor's personal guitar.
- Local BOSS livesets (`*.tsl`) are ignored and are not published.

## Artist and song disclaimer

Artist and song names identify the sound that inspired a personal tone. The guides are not official patches, are not claimed to reproduce an artist's exact equipment or settings, and are not affiliated with or endorsed by BOSS, Roland, or any referenced artist or rights holder. All trademarks and copyrighted works remain the property of their respective owners.

## License

Except where otherwise noted, the original written material in this repository is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE). You may share and adapt it for any purpose with appropriate attribution and an indication of changes.
