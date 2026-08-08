# Iron Maiden — The Trooper (Rhythm + Harmony Lead)

> This is a personal interpretation inspired by **Iron Maiden — The Trooper**, not an official setting or exact recreation.

## Overview

| Field | Value |
| --- | --- |
| Collection | Artist / song |
| Artist | Iron Maiden |
| Song | The Trooper |
| Album | *Piece of Mind* |
| Target sound | Galloping, mid-forward rhythm with a switchable harmony and solo lift |
| Intended use | Practice, rehearsal, live performance, or guitar tracking |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | Not specified |
| Last verified | 2026-08-08 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Bridge humbucker |
| Tuning | E standard: E A D G B E |
| Guitar controls | Volume 10, Tone 10 |
| Technique | Relaxed alternate-picked gallops, light palm muting, clean chord changes, controlled bends, and melodic vibrato |

## Target character

The base tone should have:

- A bright, energetic British-style crunch.
- Moderate saturation rather than modern high-gain compression.
- Strong mids that remain audible alongside bass and drums.
- Tight but not clinical low-string response.
- Clear separation during the rapid galloping rhythm.
- A small amount of filtered room ambience.
- Enough dynamic range for chord accents and melody notes to rise above muted pedal tones.

Keep Solo and Delay off for the principal rhythm sections. Engage Solo for the opening and recurring harmony melodies. Engage Solo and Delay together for the two featured guitar solos.

The Clean Boost is a Katana translation of the era’s practice of pushing Marshall amplifiers with external boosters or overdrives. These values are not reported original settings.

## Signal chain

Use a pre-amplifier Booster order in Tone Studio:

```text
Input
  -> Clean Boost
  -> Crunch Amplifier
  -> Channel EQ (Amp Out)
  -> Digital Delay (Off for rhythm and harmony; On for guitar solos)
  -> Noise Suppressor
  -> Volume Pedal
  -> Room Reverb
  -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Crunch |
| Variation | Off |
| Gain | 64 |
| Volume | 80 |
| Bass | 44 |
| Middle | 63 |
| Treble | 60 |
| Presence | 54 |
| Contour | Off |
| Cabinet Resonance | Vintage |

Crunch without Variation supplies the open, British-style foundation. Gain 64 provides sustain but retains substantially more pick definition and dynamic range than a heavily saturated Lead or Brown setting.

The elevated Middle control is important. This is not a heavily scooped metal sound: the guitar must remain clear around the bass, vocals, and second harmony line.

Vintage Cabinet Resonance adds the slightly looser response associated with a traditional cabinet. If the built-in speaker becomes indistinct at rehearsal volume, try Modern before sharply reducing Bass.

Use Master Volume and Power Control—not Channel Volume—to set physical loudness.

## Effects overview

| Block | On/Off | Type | Primary level/knob | Usage |
| --- | --- | --- | ---: | --- |
| Booster | On | Clean Boost | Effect Level 68 | Always on |
| Mod | Off | Phaser | Level 0 | Not used |
| FX | Off | Chorus | Level 0 | Not used |
| Delay | Off | Digital | Effect Level 14 | Switch on for the guitar solos |
| Reverb | On | Room | Effect Level 9 | Always on |

### Booster — Clean Boost

| Parameter | Value |
| --- | ---: |
| Type | Clean Boost |
| Drive | 7 |
| Tone | +3 |
| Bottom | -10 |
| Effect Level | 68 |
| Solo Switch | Off |
| Solo Level | 50 |
| Direct Mix | 0 |

The Clean Boost increases attack and pushes the Crunch amplifier without adding a thick second layer of distortion. The reduced Bottom prevents the bridge humbucker from making the gallop feel congested.

Keep Drive low. If the sound needs more saturation, raise amplifier Gain slightly before turning the Booster into an obvious distortion effect.

### Delay — Digital

| Parameter | Value |
| --- | ---: |
| On/Off | Off initially; On for the guitar solos |
| Type | Digital |
| Delay Time | 300 ms |
| Feedback | 14 |
| High Cut | 5.0 kHz |
| Effect Level | 14 |
| Direct Mix | 100 |

Keep Delay off for the galloping rhythm and harmonized melody sections. Switch it on with Solo for the two featured guitar solos.

The repeat should sit behind the dry guitar. If individual notes become blurred, lower Effect Level before shortening Delay Time.

### Reverb — Room

| Parameter | Value |
| --- | ---: |
| Type | Room |
| Reverb Time | 1.3 s |
| Pre Delay | 12 ms |
| Effect Level | 9 |
| Direct Mix | 100 |
| Low Cut | 160 Hz |
| High Cut | 6.3 kHz |
| Density | 6 |

The Room reverb provides a small sense of recorded space without washing out the rhythm. Its filtered low end prevents the gallop from becoming soft or distant.

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

The broad 250 Hz cut controls boxiness while the 1.6 kHz lift brings the pick attack and harmonized melodies forward. This correction is intentionally modest; the amplifier’s natural midrange remains the basis of the tone.

Low Cut removes unnecessary sub-bass, while High Cut controls the fizzy edge that can appear through headphones or Line Out.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Threshold | 32 |
| Release | 55 |

The relatively low Threshold controls idle noise without choking the open chords, melody notes, or solo sustain. Use both hands to mute rests rather than relying on a severe gate.

### Pedal FX

| Parameter | Value |
| --- | --- |
| On/Off | Off |
| Position | Input |
| Type | Pedal Wah |

### Solo

| Parameter | Value |
| --- | ---: |
| Solo On/Off | Off initially; On for harmony melodies and guitar solos |
| Solo Level | 58 |
| Solo EQ On/Off | On |
| Solo EQ Position | Amp Out |
| Low Cut | 80 Hz |
| Low Gain | 0 dB |
| Mid Frequency | 1.6 kHz |
| Mid Q | 0.7 |
| Mid Gain | +2 dB |
| High Gain | +1 dB |
| High Cut | 8.0 kHz |
| Level | +1 dB |

Solo adds a modest level increase and broad upper-mid focus without changing the amplifier gain.

Switch Solo on for the opening and recurring harmony melodies, then off when returning to the galloping rhythm. For the featured guitar solos, activate Solo and Delay together.

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
| Room/monitoring notes | Raise the combo off a resonant floor and reassess Bass, Presence, and reverb at performance volume |

For headphones, USB, or Line Out, reduce Presence or lower the Channel EQ High Cut before removing the midrange that makes the tone audible in a mix.

## Playing notes

- Keep the Clean Boost and Room reverb on throughout the song.
- Use alternate picking for the gallop and keep the wrist relaxed. Excessive tension will make the rhythm uneven and tire the picking arm.
- Palm-mute the repeated low-string notes lightly enough that their pitch remains audible.
- Allow the larger chord accents to open up more than the galloping pedal tones.
- Keep the pick angle shallow to reduce scraping and help rapid string changes.
- Switch Solo on for the signature harmony melodies. Play one genuine harmony line rather than attempting to imply both lines with extra gain.
- Keep Delay off during the harmony melodies so the two-guitar phrasing remains clear.
- Switch Solo and Delay on together for the guitar solos.
- For melodic lead playing, use controlled bends and vocal vibrato. The patch should respond to phrasing rather than burying it beneath compression.
- A real second guitarist—or separately recorded second performance—is the best way to reproduce the harmonized parts. Chorus or automatic harmonization cannot reproduce every changing interval accurately.
- When recording both harmony parts, use separate performances and pan them apart. Avoid increasing Gain to make one track sound larger.

## Adjust it for your rig

### Too bright or fizzy

1. Reduce Presence from 54 to approximately 48–51.
2. Change Channel EQ High Cut from 8.0 kHz to 6.3 kHz.
3. Reduce Treble from 60 to approximately 56–58.
4. Lower Clean Boost Tone from +3 toward 0.

### Too dark

1. Change High Cut from 8.0 kHz to 10.0 kHz.
2. Raise Presence by approximately 3–4 points.
3. Raise Clean Boost Tone from +3 toward +7.
4. Increase Treble only after confirming the guitar tone control is fully open.

### Too loose or bass-heavy

1. Reduce Bass from 44 to approximately 39–41.
2. Lower Clean Boost Bottom from -10 toward -15.
3. Change Channel EQ Low Cut from 80 Hz to 100 Hz.
4. Try Modern Cabinet Resonance at rehearsal volume.
5. Raise the combo off a resonant floor.

### Too thin

1. Raise Bass by approximately 3 points.
2. Move Clean Boost Bottom from -10 toward -5.
3. Reduce the 250 Hz cut from -2 dB to -1 dB.
4. Retain Vintage Cabinet Resonance.

### Too scooped or distant

1. Confirm Middle is set to 63.
2. Reduce the 250 Hz cut from -2 dB to -1 dB.
3. Raise the 1.6 kHz boost from +2 dB to +3 dB.
4. Do not compensate by adding large amounts of Treble.

### Too saturated or compressed

1. Reduce amplifier Gain from 64 to approximately 58–61.
2. Reduce Clean Boost Effect Level from 68 to approximately 62–65.
3. Lower Clean Boost Drive from 7 to approximately 3–5.
4. Change only one gain stage at a time.

### Needs more sustain

1. Raise amplifier Gain by 2–3 points.
2. Raise Clean Boost Effect Level to approximately 72.
3. Increase Solo Level before adding more rhythm gain.
4. Keep the Noise Suppressor Threshold low enough to preserve note decay.

### Harmony or solo does not stand out

1. Raise Solo Level from 58 to approximately 62.
2. Increase Solo EQ Level from +1 dB to +2 dB.
3. Raise the 1.6 kHz Mid Gain from +2 dB to +3 dB.
4. Do not add Delay until the dry melody is clearly audible.

### Too noisy

1. Raise Noise Suppressor Threshold from 32 toward 37–42.
2. Reduce Clean Boost Effect Level or amplifier Gain if noise remains excessive.
3. Keep Release near 55 to preserve natural note endings.
4. Avoid raising the threshold so far that it interrupts the harmony notes.

### Different pickups

- With a lower-output humbucker, raise Clean Boost Effect Level by 3–5 points before increasing amplifier Gain.
- With a very hot or active bridge humbucker, lower Gain by 3–5 points and reduce Booster Effect Level to approximately 60–64.
- With a bridge single coil, add approximately 3 points of Gain and reduce Presence if the attack becomes sharp; expect more idle noise.
- With a dark humbucker, raise Clean Boost Tone before adding amplifier Treble.

## Research notes

A 1983 interview conducted during the *Piece of Mind* era documented Dave Murray using multiple 50-watt Marshall amplifiers and cabinets, with an FET booster and graphic equalizer among his effects. Adrian Smith described using a Tube Screamer and a separate power boost for solos.

The same interview states that *Piece of Mind* was recorded at Compass Point Studios with producer Martin Birch and that the band used substantially the same equipment in the studio as onstage. It also describes the guitar amplifiers being separated in a large wooden room and extensively miked.

Those facts inform the Crunch amplifier, input boost, modest corrective EQ, room ambience, and switchable solo lift used here. The listed Katana values are a reasoned translation, not documented Iron Maiden settings.

The original recording features Dave Murray and Adrian Smith as separate lead guitarists. A single Katana patch cannot reproduce their distinct performances or the genuine twin-guitar harmonies, so this guide supplies one clear core tone suitable for either line.

## References

- [Iron Maiden official singles discography — “The Trooper”](https://www.ironmaiden.com/discography/singles/)
- [Adrian Smith and Dave Murray’s 1983 equipment and *Piece of Mind* recording interview — Guitar World](https://www.guitarworld.com/artists/interview-iron-maidens-adrian-smith-and-dave-murray-their-first-guitar-world-feature-1983)
- [Iron Maiden — “The Trooper” 2015 remaster](https://www.youtube.com/watch?v=W4DfbinBgL4)
- [Guitar World guide to relaxed gallop picking](https://www.guitarworld.com/lessons/techniques/gallop-guitar)
- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-08 | Initial documented rhythm, harmony, and solo-lift settings. |
