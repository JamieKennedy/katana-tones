# Megadeth — Tornado of Souls (Rhythm + Solo)

> This is a personal interpretation inspired by **Megadeth — Tornado of Souls**, not an official setting or exact recreation.

## Overview

| Field | Value |
| --- | --- |
| Collection | Artist / song |
| Artist | Megadeth |
| Song | Tornado of Souls |
| Album | *Rust in Peace* |
| Target sound | Tight, bright rhythm with a singing solo lift |
| Intended use | Practice, rehearsal, live performance, or guitar tracking |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | Not specified |
| Last verified | 2026-08-07 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Bridge humbucker |
| Tuning | E standard: E A D G B E |
| Guitar controls | Volume 10, Tone 10 |
| Technique | Firm alternate picking, tight palm muting, clean string changes, wide bends, and controlled vibrato |

## Target character

The base sound is a dry, upper-mid-forward thrash rhythm tone. It should have enough compression to make fast notes and harmonics jump out, but not so much gain that the main riff loses its pick attack. The low end is deliberately restrained and the midrange remains present.

For the featured solo, engage the stored Solo setting and Digital Delay. The Solo EQ adds a vocal midrange focus and the short, darkened delay supplies space without washing out fast phrases. The amp gain remains unchanged so the lead becomes louder and more lyrical rather than simply more distorted.

The T-Scream Booster is used here as a Katana input-shaping tool. This is not a claim that the same pedal or these settings were used on the recording.

## Signal chain

Use a pre-amplifier Booster order in Tone Studio:

```text
Input
  -> T-Scream Booster
  -> Lead Amplifier
  -> Channel EQ (Amp Out)
  -> Digital Delay (Off for rhythm; On for the featured solo)
  -> Noise Suppressor
  -> Volume Pedal
  -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Lead |
| Variation | Off |
| Gain | 54 |
| Volume | 80 |
| Bass | 42 |
| Middle | 57 |
| Treble | 64 |
| Presence | 58 |
| Contour | Off |
| Cabinet Resonance | Modern |

Lead without Variation provides the saturated British-style foundation while retaining a harder edge than the more compressed Brown voice. Moderate Gain preserves separation in the fast rhythm figures. The elevated Middle, Treble, and Presence settings create the bright attack, while Modern Cabinet Resonance keeps the low strings focused.

Use Master Volume and Power Control—not Channel Volume—to set physical loudness.

## Effects overview

| Block | On/Off | Type | Primary level/knob | Usage |
| --- | --- | --- | ---: | --- |
| Booster | On | T-Scream | Effect Level 76 | Always on |
| Mod | Off | Chorus | Level 0 | Not used |
| FX | Off | Parametric EQ | Level 0 | Not used |
| Delay | Off | Digital | Effect Level 18 | Switch on for the featured solo |
| Reverb | Off | Room | Effect Level 0 | Keep the rhythm and solo direct |

### Booster — T-Scream

| Parameter | Value |
| --- | ---: |
| Type | T-Scream |
| Drive | 5 |
| Tone | +4 |
| Bottom | -18 |
| Effect Level | 76 |
| Solo Switch | Off |
| Solo Level | 50 |
| Direct Mix | 0 |

The low Drive prevents a second layer of fuzzy distortion. Reduced Bottom tightens the amplifier input, while the high Effect Level adds compression and makes pick attack more immediate.

### Delay — Digital

| Parameter | Value |
| --- | ---: |
| On/Off | Off initially; On for the featured solo |
| Type | Digital |
| Delay Time | 320 ms |
| Feedback | 18 |
| High Cut | 5.0 kHz |
| Effect Level | 18 |
| Direct Mix | 100 |

Keep Delay Off for all rhythm sections. Switch it on with Solo at the start of the featured solo, then switch both off when returning to rhythm. The low Feedback and Effect Level keep the repeat behind the dry note.

## Additional tone settings

### Channel EQ

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Type | Parametric |
| Position | Amp Out |
| Low Gain | -1 dB |
| Low-Mid Frequency | 250 Hz |
| Low-Mid Q | 0.7 |
| Low-Mid Gain | -2 dB |
| High-Mid Frequency | 1.6 kHz |
| High-Mid Q | 0.7 |
| High-Mid Gain | +2 dB |
| High Gain | +1 dB |
| Low Cut | 80 Hz |
| High Cut | 8.0 kHz |
| Level | 0 dB |

The broad 250 Hz cut removes boxiness, while the broad 1.6 kHz lift brings forward pick definition and harmonics. The filters remove unnecessary sub-bass and high-gain fizz without making the tone small.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Threshold | 40 |
| Release | 48 |

Threshold 40 should control idle noise without shortening sustained lead notes. Raise it only as far as the room and pickup require.

### Pedal FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Position | Input |
| Type | Pedal Wah |

### Solo

| Parameter | Value |
| --- | ---: |
| Solo On/Off | Off initially; On for the featured solo |
| Solo Level | 62 |
| Solo EQ On/Off | On |
| Solo EQ Position | Amp Out |
| Low Cut | 80 Hz |
| Low Gain | 0 dB |
| Mid Frequency | 1.2 kHz |
| Mid Q | 0.7 |
| Mid Gain | +3 dB |
| High Gain | +1 dB |
| High Cut | 8.0 kHz |
| Level | +2 dB |

Solo increases level and adds a broad midrange lift for the featured lead. If activating Solo produces too large a jump, reduce Solo Level before removing the EQ boost.

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
| Room/monitoring notes | Raise the combo off a resonant floor; reassess Bass, Presence, and Noise Suppressor Threshold at performance volume |

## Playing notes

- Keep the Booster on for both rhythm and lead.
- Use controlled palm muting close to the bridge. The muted notes should retain pitch and attack rather than becoming featureless thumps.
- Let open chords and harmonics ring; the patch is intentionally gated less aggressively than a modern metal tone.
- Keep fast alternate-picked passages even and use both hands to silence unused strings.
- For the featured solo, switch on Solo and Delay together. Prioritize accurate bends, wide controlled vibrato, and phrasing dynamics over adding more gain.
- For recording, double-track separate rhythm performances and pan them instead of increasing Gain.

## Adjust it for your rig

### Too bright or fizzy

1. Reduce Presence from 58 to approximately 52–55.
2. Change Channel EQ High Cut from 8.0 kHz to 6.3 kHz.
3. Reduce Treble from 64 to approximately 59–61.
4. Lower T-Scream Tone from +4 toward 0.

### Too dark

1. Change High Cut from 8.0 kHz to 10.0 kHz.
2. Raise Presence by 3–4 points.
3. Raise T-Scream Tone from +4 toward +8.
4. Increase Treble only after confirming the guitar tone control is fully open.

### Too loose or bass-heavy

1. Reduce Bass from 42 to approximately 36–39.
2. Lower T-Scream Bottom from -18 toward -22.
3. Change Low Cut from 80 Hz to 100 Hz.
4. Confirm Cabinet Resonance is Modern.

### Too thin

1. Raise Bass by approximately 3 points.
2. Move T-Scream Bottom from -18 toward -12.
3. Reduce the 250 Hz cut from -2 dB to -1 dB.
4. Avoid adding gain as a substitute for body.

### Too compressed or saturated

1. Reduce amplifier Gain from 54 to approximately 49–51.
2. Reduce T-Scream Effect Level from 76 to approximately 70–72.
3. Keep Booster Drive low.
4. Change one gain stage at a time.

### Solo does not stand out

1. Raise Solo Level from 62 to approximately 66.
2. Increase Solo EQ Level from +2 dB to +3 dB.
3. Raise the 1.2 kHz Mid Gain from +3 dB to +4 dB.
4. Do not add more Delay until the dry lead is clearly audible.

### Too noisy

1. Raise Noise Suppressor Threshold from 40 toward 45–48.
2. Reduce amplifier Gain or Booster Effect Level if the noise remains excessive.
3. Keep Release near 48 so sustained notes do not end abruptly.

### Different pickups

- With a lower-output humbucker, raise Booster Effect Level by 3–5 points before increasing Gain.
- With a very hot or active bridge pickup, reduce Booster Effect Level to approximately 68–72 and lower Gain by 2–4 points.
- With a bridge single coil, add 2–3 points of Gain and reduce Presence if the attack becomes sharp; expect more idle noise.

## Research notes

Megadeth’s official album page identifies “Tornado of Souls” as part of *Rust in Peace*. In a retrospective interview, Dave Mustaine said his main amplifiers for the album were Marshall JCM800s. That documented amplifier family informs the bright, British-style foundation here, but these Katana values are a practical translation rather than reported original settings.

ZOOM’s Dave Mustaine Signature Edition patch list describes its Tornado-related rhythm sound as compressed, high-accented, less ambient, and strongly defined. It describes the companion lead sound as slightly lower gain, lyrical, singing, and harmonically rich. Those public character descriptions guide the rhythm/solo contrast in this patch; no settings have been copied between unlike devices.

The featured solo is closely associated with Marty Friedman. The same amplifier patch is retained for both roles so the guide remains practical on one Katana channel, with Solo EQ and Delay supplying the change in level, focus, and ambience.

## References

- [Megadeth — *Rust in Peace*](https://www.megadeth.com/products/rust-in-peace)
- [Dave Mustaine on recording *Rust in Peace* — Guitar World](https://www.guitarworld.com/features/megadeth-rust-never-sleeps)
- [ZOOM G2.1DM Dave Mustaine Signature Edition patch list](https://zoomcorp.com/media/documents/E_G21DM_Patch-List.pdf)
- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-07 | Initial documented rhythm and solo settings. |
