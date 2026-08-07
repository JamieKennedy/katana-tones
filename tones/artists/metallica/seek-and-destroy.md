# Metallica — Seek & Destroy (Main Riff)

> This is a personal interpretation inspired by **Metallica — Seek & Destroy**, not an official setting or exact recreation.

## Overview

| Field | Value |
| --- | --- |
| Collection | Artist / song |
| Artist | Metallica |
| Song | Seek & Destroy |
| Album | Kill ’Em All |
| Target sound | Main rhythm riff |
| Intended use | Practice, rehearsal, or live rhythm |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | Not specified |
| Last verified | 2026-08-07 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Bridge humbucker |
| Tuning | E standard: E A D G B E |
| Guitar controls | Volume 10, Tone 10 |
| Technique | Firm picking, controlled palm muting, and precise note stops |

## Target character

A raw, dry early-thrash rhythm sound with:

- Firm and percussive pick attack.
- Clear low-E-string definition.
- Crunch rather than modern high-gain compression.
- Strong midrange presence.
- Bright attack without excessive fizz.
- Tight note endings and clearly defined rests.

The RAT Booster provides the distortion character while the Lead amp supplies body and sustain.

## Signal chain

Confirm the movable block order visually in Tone Studio if your chain display differs.

```text
Input
  -> RAT Booster
  -> Lead Amplifier
  -> Channel EQ (Off)
  -> Noise Suppressor (Off)
  -> Volume Pedal
  -> Digital Delay (Off)
  -> Plate Reverb (Off)
  -> Send/Return (Post FV, Series)
  -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Lead |
| Variation | Off |
| Gain | 52 |
| Volume | 80 |
| Bass | 45 |
| Middle | 58 |
| Treble | 67 |
| Presence | 55 |
| Contour | Off |
| Cabinet Resonance | Vintage |

The Lead amp provides the core distortion, but Gain remains moderate enough to preserve the riff’s attack.

Volume at 80 gives the preamp section a strong output without requiring additional distortion. Use Master Volume and Power Control to set the physical loudness.

The relatively strong Middle setting helps retain the rawer *Kill ’Em All* character instead of producing a heavily scooped later-Metallica sound. Vintage Cabinet Resonance adds a looser, more traditional cabinet response.

## Effects overview

| Block | On/Off | Type | Primary level |
| --- | --- | --- | ---: |
| Booster | On | RAT | Effect Level 70 |
| Mod | Off | Pitch Shifter | Inactive |
| FX | Off | Parametric EQ | Inactive |
| Delay | Off | Digital | Inactive |
| Reverb | Off | Plate | Inactive |

## Booster

### RAT

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Drive | 25 |
| Tone | -10 |
| Bottom | +5 |
| Solo Switch | Off |
| Solo Level | 50 |
| Effect Level | 70 |
| Direct Mix | 0 |

The RAT supplies an early-metal distortion texture without being pushed into fuzzy saturation.

Tone at -10 softens the upper edge before it reaches the Lead amplifier. Bottom at +5 retains weight without excessive low-end boost.

The BOSS RAT model is described as modelling a Pro Co RAT. Its settings here are a Katana interpretation, not a claim about the precise pedal settings used on the recording.

## Mod

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Pitch Shifter |

This block makes no audible contribution while disabled.

## FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Parametric EQ |

This block makes no audible contribution while disabled.

## Delay

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Digital |

Keeping Delay off prevents the repeated low-string notes and rests from becoming blurred.

## Reverb

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assigned type | Plate |

The dry configuration produces tighter stops and a more immediate riff sound. Add ambience at the recording or mixing stage if required.

## Additional tone settings

### Channel EQ

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Type | Parametric |
| Position | Amp In |

The EQ does not affect the sound while the block is disabled.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | Off |
| Threshold | 35 |
| Release | 45 |

The Noise Suppressor is currently disabled. If the tone is noisy at playing volume, enable it using the existing Threshold and Release values as the starting point.

Threshold 35 should control a moderate amount of idle noise without making the riff feel heavily gated. Lower it if sustained notes are cut short.

### Pedal FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Assignment | Pedal Wah |
| Position | Input |

### Solo

| Parameter | Value |
| --- | ---: |
| On/Off | Off |
| Solo Level | 50 |
| Solo EQ | Off |

### Send/return

| Parameter | Value |
| --- | --- |
| On/Off | On |
| Position | Post FV |
| Mode | Series |
| Send Level | 50 |
| Return Level | 50 |

This setting matters only when equipment is connected to the effects loop. If nothing is connected, confirm that the loop configuration does not mute or unexpectedly alter the signal.

## Playback context

These settings are environment-dependent and may need changing without altering the core tone.

| Setting | Recommendation |
| --- | --- |
| Power Control | 0.5 W for home practice; Half for rehearsal |
| Master Volume | Set for the room after loading the tone |
| Output | Katana built-in speaker |
| Cabinet Resonance | Vintage |
| Global EQ | Off initially |
| Air Feel | Choose a neutral option when recording through USB or Line Out |

Vintage Cabinet Resonance gives the tone a looser, more traditional response. At rehearsal volume, try Modern if the low end becomes too broad or slow.

Reassess Gain, Bass, Presence, and Booster Drive whenever the physical playing volume changes.

## Playing notes

- Use a firm pick attack and play near enough to the bridge to retain definition.
- Coordinate the fretting-hand releases and picking-hand muting so rests remain abrupt.
- Use controlled palm muting on the low E string without choking every note equally.
- Let the riff’s moving notes speak clearly.
- Keep the pick angle relatively shallow to reduce scraping and fizz.
- Practise slowly enough that every stop is clean before increasing tempo.
- Favour consistent downstrokes where comfortable, but prioritise timing and note separation.

## Adjust it for your rig

### Too bright or fizzy

1. Reduce Treble from 67 to approximately 60–63.
2. Reduce Presence from 55 to approximately 48–52.
3. Lower RAT Tone from -10 to approximately -15.
4. Keep Middle near 58 so the riff remains present.

### Too dark

1. Raise RAT Tone from -10 to approximately -5 or 0.
2. Raise Presence by approximately 3–5 points.
3. Increase Treble only after adjusting the RAT Tone.
4. Confirm the guitar’s tone control is fully open.

### Too loose or bass-heavy

1. Change Cabinet Resonance from Vintage to Modern.
2. Reduce Bass from 45 to approximately 38–41.
3. Reduce RAT Bottom from +5 to 0 or -5.
4. Move the picking hand slightly closer to the bridge.

### Too thin

1. Try changing Cabinet Resonance from Vintage to Deep.
2. Raise Bass by approximately 3–5 points.
3. Raise RAT Bottom from +5 to approximately +10.
4. Avoid removing too much midrange.

### Too compressed or saturated

1. Reduce Lead Gain from 52 to approximately 47–49.
2. Reduce RAT Drive from 25 to approximately 18–22.
3. Change only one gain stage at a time.
4. Keep RAT Effect Level near 70 to preserve the amp input level.

### Needs more aggression

1. Raise RAT Drive from 25 to approximately 28–32.
2. Alternatively, raise Lead Gain by 3–5 points.
3. Do not raise both controls immediately.
4. Increase Presence slightly for more pick attack before adding substantial gain.

### Too noisy

1. Enable the Noise Suppressor.
2. Begin with Threshold 35 and Release 45.
3. Lower Threshold if sustained notes are being cut short.
4. Reduce RAT Drive or Lead Gain before using an excessively high threshold.

### Using lower-output pickups

1. Raise Lead Gain by approximately 3–5 points.
2. Increase RAT Effect Level if more input level is required.
3. Add a small amount of Presence rather than making a large Treble increase.

## Research notes

Metallica’s official discography identifies “Seek & Destroy” as a track from *Kill ’Em All*. Retrospective interviews describe the band’s early sound as developing from an aggressive, Marshall-centred rhythm approach before their later Mesa/Boogie era.

Published gear reconstructions differ on parts of the precise *Kill ’Em All* recording chain. These settings are therefore a practical Katana interpretation of the main-riff character, not a claim about Metallica’s exact studio settings.

## References

- [Metallica — Kill ’Em All](https://www.metallica.com/releases/albums/kill-em-all-album.html)
- [Metallica on their tonal evolution and the art of the riff — MusicRadar](https://www.musicradar.com/news/guitars/metallicas-james-hetfield-and-kirk-hammett-on-their-tonal-evolution-the-art-of-the-riff-and-justice-for-lars-646024)
- [James Hetfield and Kirk Hammett interview — MusicRadar](https://www.musicradar.com/news/metallica-interview-james-hetfield-kirk-hammett)
- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-07 | Initial documented settings and adjustment guidance. |
