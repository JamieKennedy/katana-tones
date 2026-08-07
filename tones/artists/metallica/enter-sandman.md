# Metallica — Enter Sandman (Main Rhythm)

> This is a personal interpretation inspired by **Metallica — Enter Sandman**, not an official setting or exact recreation.

## Overview

| Field | Value |
| --- | --- |
| Collection | Artist / song |
| Artist | Metallica |
| Song | Enter Sandman |
| Album | Metallica (*The Black Album*) |
| Target sound | Tight, muscular main rhythm guitar |
| Intended use | Practice, rehearsal, live rhythm, or rhythm tracking |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | Not specified |
| Last verified | 2026-08-07 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Bridge humbucker |
| Tuning | E standard: E A D G B E |
| Guitar controls | Volume 10, Tone 10 |
| Technique | Firm downstrokes, controlled palm muting, shallow pick angle, and abrupt note stops |

## Target character

A dense but articulate rhythm sound with:

- A hard, percussive initial attack.
- Tight low-E-string response without oversized sub-bass.
- Moderate saturation rather than fuzzy or overly compressed gain.
- A restrained mid scoop with enough low-mid body to produce the Black Album’s characteristic “bark.”
- A dry, immediate presentation that preserves the riff’s rests and groove.

The T-Scream Booster is being used as a Katana gain-shaping tool. Its low Drive and reduced Bottom tighten the amplifier input; this is not a claim that the same pedal was used on the recording.

## Signal chain

Select a Chain 1-style order in Tone Studio:

```text
Input
  -> T-Scream Booster
  -> Mod (Off)
  -> Lead Amplifier
  -> Channel EQ (Amp Out)
  -> FX (Off)
  -> Noise Suppressor
  -> Volume Pedal
  -> Digital Delay (Off)
  -> Plate Reverb (Off)
  -> Send/Return (Off, Post FV)
  -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Lead |
| Variation | On |
| Gain | 58 |
| Volume | 80 |
| Bass | 43 |
| Middle | 45 |
| Treble | 60 |
| Presence | 54 |
| Contour | Off |
| Cabinet Resonance | Modern |

Lead with Variation supplies the dense, smooth high-gain foundation. Gain remains below maximum so palm-muted notes retain their edges instead of collapsing into compression.

Modern Cabinet Resonance keeps the low end focused. The modest Middle setting avoids the hollow sound produced by completely removing the midrange; the post-amplifier EQ performs the more selective shaping.

Use Master Volume and Power Control—not Channel Volume—to set physical loudness.

## Effects overview

| Block | On/Off | Type | Primary level |
| --- | --- | --- | ---: |
| Booster | On | T-Scream | Effect Level 78 |
| Mod | Off | Chorus | Inactive |
| FX | Off | Parametric EQ | Inactive |
| Delay | Off | Digital | Inactive |
| Reverb | Off | Plate | Inactive |

## Booster

### T-Scream

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Drive | 6 |
| Tone | -5 |
| Bottom | -20 |
| Effect Level | 78 |
| Solo Switch | Off |
| Solo Level | 50 |
| Direct Mix | 0 |

The low Drive avoids adding a second layer of fuzzy distortion. Bottom at -20 removes loose bass before the amplifier, while the strong Effect Level pushes the Lead preamp and improves pick response.

If the sound becomes nasal, reduce Effect Level before increasing Bass.

## Mod

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Chorus |

This block makes no audible contribution while disabled.

## FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Parametric EQ |

The separate Channel EQ performs the required tonal correction, leaving the FX block available for another assignment.

## Delay

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Digital |

Delay is disabled so repeated low-string notes and rests remain distinct.

## Reverb

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Plate |

The core patch is intentionally dry. Add room ambience during recording or through the venue rather than softening the riff inside the tone.

## Additional tone settings

### Channel EQ

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Type | Parametric |
| Position | Amp Out |
| Low Gain | 0 dB |
| Low-Mid Frequency | 160 Hz |
| Low-Mid Q | 0.5 |
| Low-Mid Gain | +2 dB |
| High-Mid Frequency | 800 Hz |
| High-Mid Q | 1.0 |
| High-Mid Gain | -3 dB |
| High Gain | +1 dB |
| Low Cut | 80 Hz |
| High Cut | 8.0 kHz |
| Level | 0 dB |

The broad 160 Hz lift adds controlled weight and low-mid punch. The small 800 Hz cut provides the familiar scoop without removing all of the guitar’s body. Low Cut prevents unnecessary sub-bass from making the built-in speaker feel slow, while High Cut controls high-gain fizz.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Threshold | 42 |
| Release | 48 |

Threshold 42 should control idle noise while allowing held chords to decay. Raise it only as far as necessary; an aggressive threshold will make note endings sound artificial.

### Pedal FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Type | Wah 95E |
| Position | Input |

The wah assignment is inactive. A separate lead patch is recommended for the solo.

### Solo

| Parameter | Value |
| --- | ---: |
| On/Off | Off |
| Solo Level | 50 |
| Solo EQ | Off |

### Send/return

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Position | Post FV |
| Mode | Series |
| Send Level | 50 |
| Return Level | 50 |

## Playback context

These settings are room-dependent and should not replace adjustments to the stored tone.

| Setting | Recommendation |
| --- | --- |
| Power Control | 0.5 W for home practice; Half for rehearsal |
| Master Volume | Set for the room after loading the tone |
| Output | Katana built-in speaker |
| Air Feel | Neutral option for USB or Line Out |
| Global EQ | Off initially |
| Room/monitoring notes | Keep the combo off the floor if the bass becomes boomy; reassess Bass and Presence at performance volume |

For headphones or Line Out, the tone may initially seem brighter than it does through the built-in speaker. Adjust High Cut or Presence before changing the entire amplifier EQ.

## Playing notes

- Pick firmly, but avoid digging so deeply between the strings that the attack becomes scratchy.
- Use controlled palm muting near the bridge. The muted notes should remain pitched rather than becoming featureless thumps.
- Make rests decisive with both hands; the riff’s silence is part of its impact.
- Let the moving notes and larger chord accents breathe more than the repeated low-E notes.
- Keep the picking hand consistent. Much of the sound’s apparent compression comes from even playing.
- For recording, double-track separate performances and pan them rather than adding more gain to one take.
- Use a separate clean patch for the intro and a wah/delay lead patch for the solo.

## Adjust it for your rig

### Too bright or fizzy

1. Reduce Presence from 54 to approximately 48–51.
2. Change Channel EQ High Cut from 8.0 kHz to 6.3 kHz.
3. Reduce Treble from 60 to approximately 55–57.
4. Lower T-Scream Tone from -5 to approximately -10.

### Too dark

1. Change High Cut from 8.0 kHz to 10.0 kHz.
2. Raise Presence by approximately 3–5 points.
3. Raise T-Scream Tone from -5 to 0.
4. Increase Treble only after checking the guitar’s tone control.

### Too loose or bass-heavy

1. Reduce Bass from 43 to approximately 37–40.
2. Lower T-Scream Bottom from -20 to approximately -25.
3. Change Low Cut from 80 Hz to 100 Hz.
4. Confirm Cabinet Resonance is set to Modern.

### Too thin

1. Raise Bass by approximately 3 points.
2. Increase the 160 Hz Low-Mid Gain from +2 dB to +3 dB.
3. Raise T-Scream Bottom toward -15.
4. Avoid adding large amounts of gain as a substitute for body.

### Too scooped or hollow

1. Reduce the 800 Hz cut from -3 dB to -1 or -2 dB.
2. Raise the amplifier Middle control from 45 to approximately 48–52.
3. Leave the 160 Hz boost unchanged initially.

### Too compressed or saturated

1. Reduce amplifier Gain from 58 to approximately 52–55.
2. Reduce T-Scream Effect Level from 78 to approximately 70–74.
3. Keep Booster Drive low.
4. Change one gain stage at a time.

### Needs more aggression

1. Raise Presence by 2–3 points.
2. Raise T-Scream Effect Level to approximately 82.
3. If necessary, increase amplifier Gain by no more than 3 points.
4. Check pick technique before adding more distortion.

### Too noisy

1. Raise Noise Suppressor Threshold from 42 toward 47–50.
2. Reduce amplifier Gain or Booster Effect Level if the noise remains excessive.
3. Keep Release near 48 so the gate does not clamp down abruptly.

### Different pickups

- With a lower-output humbucker, raise Booster Effect Level by 3–5 points before increasing amplifier Gain.
- With a very hot or active bridge pickup, reduce Booster Effect Level to approximately 68–72 and lower Gain by 2–4 points.
- With a bridge single coil, increase Gain slightly and reduce Presence if the attack becomes sharp; expect more idle noise.

## Research notes

“Enter Sandman” is played in E standard. Kirk Hammett has specifically described writing the riff in E rather than a dropped tuning.

In a 1991 interview, James Hetfield said the album retained his Mesa/Boogie Simul-Class Mark II foundation. He also explained that the previous album’s extreme scoop lacked body and that adding some midrange improved the new guitar sound. Later, he described the Black Album development as adding low-mid “bark” for a more percussive relationship with the drums.

These Katana settings translate those broad characteristics into a single-combo rhythm patch. They do not attempt to duplicate the recording’s microphones, studio processing, layered performances, or complete amplifier blend.

## References

- [Metallica — The Black Album](https://www.metallica.com/releases/albums/the-black-album.html)
- [Metallica discuss the Black Album and the origin of “Enter Sandman” — Guitar World](https://www.guitarworld.com/features/metallica-the-black-album)
- [Metallica’s 1991 Black Album interview — Guitar World](https://www.guitarworld.com/features/metallica-black-album-1991-interview)
- [James Hetfield on midrange, low-mid “bark,” and gain — Guitar World](https://www.guitarworld.com/features/james-hetfield-death-magnetic-2008)
- [Bob Rock’s Black Album track-by-track interview — MusicRadar](https://www.musicradar.com/news/bob-rock-metallica-black-album-interview)
- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-07 | Initial documented main-rhythm settings and adjustment guidance. |
