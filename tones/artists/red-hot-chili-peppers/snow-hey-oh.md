# Snow (Hey Oh) — Clean Arpeggio Tone

> This is a personal interpretation inspired by **Red Hot Chili Peppers — Snow (Hey Oh)**, not an official or exact recreation.

## Overview

| Field | Value |
| --- | --- |
| Collection | Artist/song |
| Artist | Red Hot Chili Peppers |
| Song | Snow (Hey Oh) |
| Target sound | Clear, lightly compressed clean tone for the main arpeggio, with an optional octave-rich outro sound |
| Intended use | Practice, recording, built-in speaker, headphones, or line out |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | BOSS Tone Studio for KATANA Gen 3 PC; parameter guide revision 01 |
| Last verified | 2026-08-07 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Neck single coil |
| Tuning | E standard |
| Guitar controls | Volume 10; tone approximately 8 |
| Technique | Medium-light pick, even alternate picking, relaxed fretting hand, and controlled hammer-ons and pull-offs |

## Target character

The main sound should remain clean when individual notes are played firmly, but it should not feel sterile. A small amount of compression keeps the rapid pattern even, while the Pushed amp supplies the rounded midrange and slight elasticity associated with a loud clean rock amplifier.

The recording includes octave processing during the outro. The optional pitch-shifter configuration below approximates that broader, organ-like texture, but it is not intended to duplicate the recording’s layered studio arrangement.

## Signal chain

```text
Input -> Mod: Compressor -> FX: Pitch Shifter (stored Off; switch on for outro) -> Pushed Amp
      -> Channel EQ (Amp Out) -> Noise Suppressor -> Volume Pedal
      -> Reverb -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Pushed |
| Variation | Off |
| Gain | 23 |
| Volume | 75 |
| Bass | 42 |
| Middle | 58 |
| Treble | 60 |
| Presence | 52 |
| Contour | Off |
| Cabinet Resonance | Vintage |

Keep the Gain low enough that the main riff stays clean. The Pushed character is being used for its touch response and midrange rather than obvious overdrive.

## Effects overview

| Block | On/Off | Type | Primary level/knob | Usage |
| --- | --- | --- | ---: | --- |
| Mod | On | Compressor | Level 55 | Main tone |
| FX | Off | Pitch Shifter | Direct Mix 80 | Switch on for the octave-rich outro |
| Reverb | On | Room | Effect Level 10 | Main tone |

### Mod

| Parameter | Value |
| --- | ---: |
| Type | Compressor |
| Compressor Type | Light |
| Sustain | 30 |
| Attack | 68 |
| Level | 55 |
| Tone | +6 |

This is intentionally moderate compression. It should even out the pattern without flattening the pick attack or excessively amplifying string noise.

### FX — optional outro

Store this block **Off** for the main tone. Switch it on during the octave-rich outro if desired.

| Parameter | Value |
| --- | ---: |
| Type | Pitch Shifter |
| Voice | 2VOICE |
| PS1 Pitch | +12 |
| PS1 Level | 42 |
| PS1 Mode | Fast |
| PS1 Fine | 0 |
| PS1 Pre Delay | 0 ms |
| PS1 Feedback | 0 |
| PS2 Pitch | -12 |
| PS2 Level | 30 |
| PS2 Mode | Fast |
| PS2 Fine | 0 |
| PS2 Pre Delay | 0 ms |
| Direct Mix | 80 |

The built-in pitch shifter may sound less smooth than the polyphonic studio octave effect when fed full chords. Clean muting and clearly articulated notes will improve its tracking.

### Reverb

| Parameter | Value |
| --- | ---: |
| Type | Room |
| Reverb Time | 1.5 s |
| Pre Delay | 10 ms |
| Effect Level | 10 |
| Direct Mix | 100 |
| Low Cut | 160 Hz |
| High Cut | 6.3 kHz |
| Density | 7 |

## Additional tone settings

### Channel EQ

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Type | Parametric |
| Position | Amp Out |
| Low Gain | -2 dB |
| Low-Mid Frequency | 250 Hz |
| Low-Mid Q | 0.7 |
| Low-Mid Gain | -2 dB |
| High-Mid Frequency | 2.0 kHz |
| High-Mid Q | 0.7 |
| High-Mid Gain | +2 dB |
| High Gain | -1 dB |
| Low Cut | 80 Hz |
| High Cut | 10.0 kHz |
| Level | 0 dB |

The broad 2 kHz lift helps the individual notes speak, while the low-mid reduction prevents the riff from becoming cloudy.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Threshold | 18 |
| Release | 60 |

If the ends of notes disappear unnaturally, lower Threshold before changing anything else.

## Playback context

These settings describe a practical starting environment rather than mandatory stored settings.

| Setting | Value |
| --- | --- |
| Power Control | 0.5 W for home practice; Half for rehearsal |
| Master Volume | Start around 10–11 o’clock and adjust for the room |
| Output | Built-in speaker |
| Air Feel | Blend when using Phones, Line Out, or USB |
| Global EQ | Off |
| Room/monitoring notes | Keep the amplifier off the floor if the low notes become boomy; evaluate brightness from playing position rather than directly in front of the speaker |

## Playing notes

- Keep the pick movement small and let the compressor support consistency rather than attacking every note harder.
- The tone should be clean during single-note playing, with only a trace of hair when several strings are struck firmly.
- Briefly release fretting pressure between phrases to control sympathetic string noise.
- For the wider chorus strums, pick slightly farther from the bridge and use a lighter touch.
- Assign the FX block to a footswitch if you want the optional octave sound available for the outro.

## Adjust it for your rig

- **Too bright:** Lower Presence first, then reduce Treble. Avoid immediately turning down the guitar tone because that also softens articulation.
- **Too dark:** Raise Presence by 3–5 points or move the guitar tone toward 10.
- **Too loose or bass-heavy:** Lower Bass to 37 or increase the Channel EQ low cut to 100 Hz.
- **Too noisy:** Reduce Compressor Sustain, then raise the noise-suppressor Threshold in small steps. Avoid settings high enough to truncate notes.
- **Different pickups:** For a brighter bridge single coil, lower Treble and Presence by about 4 points. For a humbucker, reduce Gain to 18, Bass to 38, and Compressor Sustain to 24.
- **Too clean or stiff:** Raise Gain to 27–30. Stop once hard chord attacks begin producing audible crunch.
- **Notes sound squashed:** Reduce Compressor Sustain to 22 or raise Attack slightly.
- **Optional octave effect glitches:** Play fewer simultaneous notes, mute unused strings carefully, or reduce both shifted-voice levels.

## References

- [John Frusciante’s 2006 Guitar Player interview transcription](https://invisible-movement.net/press/2006-11-guitarplayer) — documents the octave processing used during the outro.
- [John Frusciante and Ryan Hewitt interview — Tape Op](https://tapeop.com/interviews/61/john-frusciante) — recording approach and the importance of performance to the resulting guitar sound.
- [John Frusciante’s 2006 Stadium Arcadium interview — MusicRadar](https://www.musicradar.com/news/classic-interview-john-frusciante-red-hot-chili-peppers)
- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)
- [BOSS Katana-100 Gen 3 product page](https://www.boss.info/uk/products/katana-100_gen_3/)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-07 | Removed unused disabled effects and retained the stored-Off pitch shifter with its outro activation note. |
| 2026-08-07 | Initial documented settings for the main clean arpeggio and optional octave-rich outro. |
