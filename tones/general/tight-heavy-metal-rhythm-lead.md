# Tight Heavy Metal Rhythm + Lead

## Overview

| Field | Value |
| --- | --- |
| Collection | General |
| Artist | Not applicable |
| Song | Not applicable |
| Target sound | Very tight, aggressive heavy-metal rhythm with enough mids and sustain for riffs and solos |
| Intended use | Practice, rehearsal, live performance, or guitar tracking |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | BOSS Tone Studio for KATANA Gen 3; version not specified |
| Last verified | 2026-08-10 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Bridge humbucker; optional neck pickup for rounder leads |
| Tuning | E standard or Drop D; suitable for lower tunings after the low-end adjustments below |
| Guitar controls | Volume 10, Tone 10 |
| Technique | Firm palm muting close to the bridge, controlled pick depth, decisive two-hand muting, and wide controlled vibrato for leads |

## Target character

This is a modern, tight heavy-metal sound designed around one core gain structure. Palm-muted notes should hit hard and stop cleanly, rapid riffs should retain separation, and sustained notes should remain full enough for lead playing.

The tone avoids an extreme mid scoop. Keeping useful midrange makes riffs audible beside drums and gives solos a vocal quality. A low-drive T-Scream removes excess bass before the amplifier, while moderate amplifier gain prevents fast notes from smearing together.

For solos, engage the stored Solo setting and Digital Delay. This adds level, midrange focus, and a short repeat without changing the underlying rhythm response.

## Signal chain

```text
Input
  -> T-Scream Booster
  -> Lead Amplifier
  -> Channel EQ (Amp Out)
  -> Digital Delay (Off for rhythm; On for solos)
  -> Room Reverb
  -> Noise Suppressor
  -> Volume Pedal
  -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Lead |
| Variation | On |
| Gain | 50 |
| Volume | 80 |
| Bass | 40 |
| Middle | 57 |
| Treble | 60 |
| Presence | 52 |
| Contour | Off |
| Cabinet Resonance | Modern |

Lead with Variation supplies dense saturation, but Gain remains moderate so the attack survives. The reduced Bass and Modern Cabinet Resonance keep muted low strings controlled. The elevated Middle prevents the rhythm sound becoming hollow and gives the Solo EQ a strong foundation.

Use Master Volume and Power Control—not Channel Volume—to set physical loudness.

## Effects overview

| Block | On/Off | Type | Primary level/knob | Usage |
| --- | --- | --- | ---: | --- |
| Booster | On | T-Scream | Effect Level 76 | Always on |
| Mod | Off | Chorus | Level 0 | Not used |
| FX | Off | Parametric EQ | Level 0 | Not used |
| Delay | Off | Digital | Effect Level 16 | Switch on for solos |
| Reverb | On | Room | Effect Level 6 | Always on |

### Booster — T-Scream

| Parameter | Value |
| --- | ---: |
| Type | T-Scream |
| Drive | 3 |
| Tone | +3 |
| Bottom | -24 |
| Effect Level | 76 |
| Solo Switch | Off |
| Solo Level | 50 |
| Direct Mix | 0 |

Drive stays very low because the Booster is shaping the amplifier input rather than supplying the main distortion. Bottom at -24 removes loose bass before it reaches the high-gain preamp. Effect Level supplies the push and compression required for immediate palm-muted attack.

### Delay — Digital

| Parameter | Value |
| --- | ---: |
| On/Off | Off initially; On for solos |
| Type | Digital |
| Delay Time | 300 ms |
| Feedback | 16 |
| High Cut | 4.0 kHz |
| Effect Level | 16 |
| Direct Mix | 100 |

Keep Delay off for rhythm. The dark, low-level repeat adds depth to sustained lead notes without obscuring quick phrases.

### Reverb — Room

| Parameter | Value |
| --- | ---: |
| Type | Room |
| Reverb Time | 1.2 s |
| Pre Delay | 10 ms |
| Effect Level | 6 |
| Direct Mix | 100 |
| Low Cut | 200 Hz |
| High Cut | 5.0 kHz |
| Density | 5 |

The reverb is intentionally subtle and filtered. It prevents the patch sounding unnaturally dry while preserving the edges of palm-muted notes.

## Additional tone settings

### Channel EQ

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Type | Parametric |
| Position | Amp Out |
| Low Gain | 0 dB |
| Low-Mid Frequency | 250 Hz |
| Low-Mid Q | 0.7 |
| Low-Mid Gain | -2 dB |
| High-Mid Frequency | 1.6 kHz |
| High-Mid Q | 0.7 |
| High-Mid Gain | +2 dB |
| High Gain | 0 dB |
| Low Cut | 80 Hz |
| High Cut | 8.0 kHz |
| Level | 0 dB |

The broad 250 Hz cut reduces boxiness and low-mid congestion. The broad 1.6 kHz lift restores pick definition and helps solos project. Low Cut removes unnecessary sub-bass, while High Cut controls high-gain fizz.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Threshold | 43 |
| Release | 52 |

This should produce clean stops while allowing sustained lead notes to decay naturally. Set Threshold only as high as necessary for the guitar and room.

### Pedal FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Position | Input |
| Type | Pedal Wah |

### Solo

| Parameter | Value |
| --- | ---: |
| Solo On/Off | Off initially; On for solos |
| Solo Level | 60 |
| Solo EQ On/Off | On |
| Solo EQ Position | Amp Out |
| Low Cut | 100 Hz |
| Low Gain | 0 dB |
| Mid Frequency | 1.2 kHz |
| Mid Q | 0.7 |
| Mid Gain | +3 dB |
| High Gain | +1 dB |
| High Cut | 8.0 kHz |
| Level | +2 dB |

Engaging Solo raises the output and adds a broad vocal-mid lift. It does not increase amplifier gain, so lead notes become more prominent without turning mushy.

Switch Solo and Delay on together for lead sections. With a suitable controller, assign them to separate switches; alternatively, copy the patch to a second channel with both already enabled.

### Send/return

| Parameter | Value |
| --- | ---: |
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
| Air Feel | Blend for Phones, Line Out, or USB |
| Global EQ | Off initially |
| Room/monitoring notes | Raise the combo off a resonant floor and reassess Bass, Presence, and Noise Suppressor Threshold at performance volume |

## Playing notes

- Keep the Booster on for rhythm and lead.
- For palm muting, rest the picking-hand edge close enough to the bridge that each low note retains a recognisable pitch.
- Use a shallow pick angle and avoid burying the pick deeply between the strings.
- Let larger chords breathe slightly more than repeated muted notes.
- Use both hands to silence unused strings; a tight patch exposes sympathetic ringing.
- For leads, engage Solo and Delay. Stay on the bridge humbucker for sharper attack or use a neck pickup for a rounder, smoother voice.
- If using the neck pickup, reduce guitar Tone slightly only when the top end remains too sharp.
- For recording, double-track separate rhythm performances instead of increasing Gain.

## Adjust it for your rig

### Too bright or fizzy

1. Reduce Presence from 52 to approximately 47–49.
2. Change Channel EQ High Cut from 8.0 kHz to 6.3 kHz.
3. Reduce Treble from 60 to approximately 56–58.
4. Lower T-Scream Tone from +3 toward 0.

### Too dark

1. Change High Cut from 8.0 kHz to 10.0 kHz.
2. Raise Presence by approximately 3 points.
3. Raise T-Scream Tone from +3 toward +7.
4. Increase Treble only after confirming the guitar tone control is fully open.

### Too loose or bass-heavy

1. Reduce Bass from 40 to approximately 35–37.
2. Lower T-Scream Bottom from -24 toward -28.
3. Change Channel EQ Low Cut from 80 Hz to 100 Hz.
4. Confirm Cabinet Resonance is Modern.
5. For Drop C or lower, make the Low Cut change before increasing Noise Suppressor Threshold.

### Too thin

1. Raise Bass by 3–4 points.
2. Move T-Scream Bottom from -24 toward -18.
3. Reduce the 250 Hz cut from -2 dB to -1 dB.
4. Avoid adding amplifier Gain as a substitute for low-mid body.

### Riffs lack definition

1. Reduce amplifier Gain from 50 to approximately 46–48.
2. Raise the 1.6 kHz EQ boost from +2 dB to +3 dB.
3. Raise Booster Effect Level by 2–3 points.
4. Check pick depth and muting position before making larger EQ changes.

### Too compressed

1. Switch Variation off and compare the response.
2. Reduce Booster Effect Level from 76 to approximately 70–72.
3. Reduce amplifier Gain by 3–5 points.
4. Change only one gain stage at a time.

### Solo does not stand out

1. Raise Solo Level from 60 to approximately 64–66.
2. Increase Solo EQ Level from +2 dB to +3 dB.
3. Raise Mid Gain from +3 dB to +4 dB.
4. Keep amplifier Gain unchanged.

### Too noisy

1. Raise Noise Suppressor Threshold from 43 toward 47–50.
2. Reduce amplifier Gain or Booster Effect Level if excessive noise remains.
3. Keep Release near 52 so sustained notes are not cut off abruptly.
4. Move away from screens, power supplies, and other interference sources.

### Different pickups

- With a lower-output humbucker, raise Booster Effect Level by 3–5 points before increasing Gain.
- With a very hot or active humbucker, reduce Booster Effect Level to approximately 68–72 and lower Gain by 2–4 points.
- With a bridge single coil, add 2–3 points of Gain and reduce Presence if the attack becomes sharp; expect more idle noise.
- With a dark humbucker, raise T-Scream Tone before increasing amplifier Treble.

## References

- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)
- [BOSS Katana-100 Gen 3 product information](https://www.boss.info/uk/products/katana-100_gen_3/)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-10 | Initial tight heavy-metal rhythm and lead settings. |
