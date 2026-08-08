# Metallica — Master of Puppets (Main Rhythm)

> This is a personal interpretation inspired by **Metallica — Master of Puppets**, not an official setting or exact recreation.

## Overview

| Field | Value |
| --- | --- |
| Collection | Artist / song |
| Artist | Metallica |
| Song | Master of Puppets |
| Album | *Master of Puppets* |
| Target sound | Dry, tightly scooped, percussive main rhythm guitar |
| Intended use | Practice, rehearsal, live rhythm, or rhythm tracking |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | Not specified |
| Last verified | 2026-08-08 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Bridge humbucker |
| Tuning | E standard: E A D G B E |
| Guitar controls | Volume 10, Tone 10 |
| Technique | Downstroke-dominant picking, firm palm muting, shallow pick angle, and precise two-hand muting |

## Target character

The main rhythm sound should have:

- A hard, immediate pick attack.
- Tight low-E response that remains pitched under palm muting.
- Dense saturation without fuzzy edges or excessive compression.
- A pronounced but selective midrange scoop.
- Enough upper-mid presence for fast chromatic notes to remain distinct.
- A dry presentation with abrupt, controlled note endings.

The recording’s layered amplifiers, cabinets, microphones, analogue tape, and multiple performances cannot be reproduced by one combo patch. This guide instead concentrates on the attack, gain structure, frequency balance, and playing response needed for a convincing single-guitar interpretation.

The T-Scream Booster is used as a Katana input-shaping tool. Its inclusion is not a claim that the same pedal or these settings were used on the recording.

## Signal chain

Use a pre-amplifier Booster order in Tone Studio:

```text
Input
  -> T-Scream Booster
  -> Lead Amplifier
  -> Channel EQ (Amp Out)
  -> Noise Suppressor
  -> Volume Pedal
  -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Lead |
| Variation | On |
| Gain | 52 |
| Volume | 80 |
| Bass | 44 |
| Middle | 40 |
| Treble | 61 |
| Presence | 56 |
| Contour | Off |
| Cabinet Resonance | Modern |

Lead with Variation provides the dense, cascading high-gain foundation. Gain is deliberately moderate: the Booster supplies input compression and focus while the amplifier retains enough headroom for individual notes to stay separate.

The amplifier Middle control is reduced but not removed. A more selective post-amplifier cut supplies the characteristic scoop without making the guitar disappear beside drums or bass.

Modern Cabinet Resonance keeps fast low-string passages focused. Use Master Volume and Power Control—not Channel Volume—to set physical loudness.

## Effects overview

| Block | On/Off | Type | Primary level/knob | Usage |
| --- | --- | --- | ---: | --- |
| Booster | On | T-Scream | Effect Level 74 | Always on |
| Mod | Off | Chorus | Level 0 | Not used |
| FX | Off | Parametric EQ | Level 0 | Not used |
| Delay | Off | Digital | Effect Level 0 | Not used |
| Reverb | Off | Room | Effect Level 0 | Keep the rhythm tone dry |

### Booster — T-Scream

| Parameter | Value |
| --- | ---: |
| Type | T-Scream |
| Drive | 4 |
| Tone | +2 |
| Bottom | -22 |
| Effect Level | 74 |
| Solo Switch | Off |
| Solo Level | 50 |
| Direct Mix | 0 |

Low Drive avoids adding a fuzzy second layer of distortion. Bottom at -22 removes loose bass before the amplifier, while Effect Level 74 pushes and compresses the Lead preamp.

Tone is nearly neutral because the amplifier and Channel EQ already provide sufficient attack. If the sound becomes nasal or overly compressed, lower Effect Level before adding Bass or Gain.

## Additional tone settings

### Channel EQ

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Type | Parametric |
| Position | Amp Out |
| Low Gain | 0 dB |
| Low-Mid Frequency | 125 Hz |
| Low-Mid Q | 0.5 |
| Low-Mid Gain | +1 dB |
| High-Mid Frequency | 800 Hz |
| High-Mid Q | 0.7 |
| High-Mid Gain | -4 dB |
| High Gain | +1 dB |
| Low Cut | 80 Hz |
| High Cut | 8.0 kHz |
| Level | 0 dB |

The broad 800 Hz cut creates the main midrange scoop while leaving the amplifier’s underlying midrange intact. The small 125 Hz lift restores controlled weight after the input Booster and Low Cut have tightened the bass.

The 80 Hz Low Cut prevents unnecessary sub-bass from slowing the built-in speaker. The 8.0 kHz High Cut controls high-gain fizz without removing the pick edge.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Threshold | 44 |
| Release | 48 |

Threshold 44 should control idle noise and support sharp rests without completely swallowing sustained chords. Raise it only as far as the guitar and room require.

### Pedal FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Position | Input |
| Type | Pedal Wah |

### Solo

| Parameter | Value |
| --- | ---: |
| On/Off | Off |
| Solo Level | 50 |
| Solo EQ | Off |

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

For headphones, USB, or Line Out, the patch may sound brighter and more processed than it does through the built-in speaker. Adjust Channel EQ High Cut or Presence before changing the complete amplifier balance.

## Playing notes

- Keep the Booster on throughout the distorted rhythm sections.
- Pick firmly with a shallow pick angle; excessive pick depth produces scraping and slows the picking hand.
- Use controlled palm muting near the bridge. The low-E notes should remain clearly pitched rather than becoming featureless thumps.
- Coordinate both hands so rests end decisively. The patch is tight, but it cannot substitute for clean muting.
- Use consistent, downstroke-dominant picking for the main rhythm feel. Relax the wrist and forearm instead of forcing every stroke.
- Let larger chord accents breathe slightly more than repeated muted notes.
- Practise difficult transitions slowly enough that every attack and stop is even before increasing tempo.
- For recording, layer separate performances rather than increasing Gain. Even two tightly played tracks will sound larger and clearer than one excessively saturated track.
- Use separate patches for the clean middle section and lead guitars.

## Adjust it for your rig

### Too bright or fizzy

1. Reduce Presence from 56 to approximately 50–53.
2. Change Channel EQ High Cut from 8.0 kHz to 6.3 kHz.
3. Reduce Treble from 61 to approximately 56–58.
4. Lower T-Scream Tone from +2 toward -3.

### Too dark

1. Change High Cut from 8.0 kHz to 10.0 kHz.
2. Raise Presence by approximately 3 points.
3. Raise T-Scream Tone from +2 toward +6.
4. Increase Treble only after confirming the guitar tone control is fully open.

### Too loose or bass-heavy

1. Reduce Bass from 44 to approximately 38–41.
2. Lower T-Scream Bottom from -22 toward -26.
3. Change Channel EQ Low Cut from 80 Hz to 100 Hz.
4. Confirm Cabinet Resonance is set to Modern.
5. Raise the combo off a resonant floor before making larger EQ changes.

### Too thin

1. Raise Bass by approximately 3 points.
2. Move T-Scream Bottom from -22 toward -16.
3. Increase the 125 Hz Low-Mid Gain from +1 dB to +2 dB.
4. Avoid adding Gain as a substitute for body.

### Too scooped or hollow

1. Reduce the 800 Hz cut from -4 dB to -2 or -3 dB.
2. Raise amplifier Middle from 40 to approximately 44–47.
3. Leave the low-frequency settings unchanged initially.

### Too compressed or saturated

1. Reduce amplifier Gain from 52 to approximately 47–49.
2. Reduce T-Scream Effect Level from 74 to approximately 68–71.
3. Keep Booster Drive at 4 or lower.
4. Change one gain stage at a time.

### Not aggressive enough

1. Increase Presence by 2–3 points.
2. Raise T-Scream Effect Level to approximately 78.
3. If necessary, raise amplifier Gain by no more than 3 points.
4. Check pick attack and palm-mute position before adding more distortion.

### Too noisy

1. Raise Noise Suppressor Threshold from 44 toward 48–52.
2. Reduce Booster Effect Level or amplifier Gain if the noise remains excessive.
3. Keep Release near 48 so sustained notes do not end unnaturally.
4. Move away from screens, power supplies, and other interference sources before using a very high threshold.

### Different pickups

- With a lower-output humbucker, raise Booster Effect Level by 3–5 points before increasing amplifier Gain.
- With a very hot or active bridge humbucker, reduce Booster Effect Level to approximately 66–70 and lower Gain by 2–4 points.
- With a bridge single coil, add 2–3 points of Gain and reduce Presence if the attack becomes sharp; expect more idle noise.
- With a dark humbucker, raise T-Scream Tone before increasing amplifier Treble.

## Research notes

Metallica recorded *Master of Puppets* at Sweet Silence Studios with Flemming Rasmussen. Rasmussen has described the rhythm sound as coming from a Mesa/Boogie Mark II C+ used as a preamplifier with a 100-watt Marshall power stage and 4×12 cabinets. The Katana Lead voice and post-amplifier EQ translate the broad cascading-gain and sculpted-EQ characteristics of that arrangement rather than reproducing its controls literally.

Rasmussen also described the title track as containing numerous layered melody guitars. Consequently, the finished record’s scale cannot be recreated simply by increasing the gain of one patch.

The song is played in E standard for practical performance. The guide targets the primary distorted rhythm role and does not attempt to combine the clean interlude or lead effects into the same channel.

## References

- [Metallica — *Master of Puppets*](https://www.metallica.com/releases/albums/master-of-puppets-album.html)
- [Flemming Rasmussen on producing and recording *Master of Puppets* — MusicRadar](https://www.musicradar.com/artists/producers-engineers/all-the-albums-i-did-with-metallica-were-recorded-on-24-track-analogue-tape-theres-not-a-computer-in-sight-how-flemming-rasmussen-produced-metallicas-classic-master-of-puppets)
- [How to play “Master of Puppets” in standard tuning — Guitar World](https://www.guitarworld.com/lessons/how-to-play-master-of-puppets-on-guitar)
- [MESA/Boogie Mark IIC+ design and controls — Gibson](https://www.gibson.com/products/mesa-boogie-mark-iic-head)
- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-08 | Initial documented main-rhythm settings and adjustment guidance. |
