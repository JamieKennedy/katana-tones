# End of Beginning — Warm Chorus Rhythm Tone

> This is a personal interpretation inspired by **Djo — End of Beginning**, not an official or exact recreation.

## Overview

| Field | Value |
| --- | --- |
| Collection | Artist/song |
| Artist | Djo |
| Song | End of Beginning |
| Target sound | Warm, compressed, lightly driven rhythm guitar with slow chorus movement and restrained ambience |
| Intended use | Practice, recording, built-in speaker, headphones, or line out |
| Katana model | BOSS Katana-100 Gen 3 |
| Tone Studio version | BOSS Tone Studio for KATANA Gen 3 PC; parameter guide revision 01 |
| Last verified | 2026-08-07 |

## Playing setup

| Setting | Value |
| --- | --- |
| Recommended pickup | Bridge humbucker |
| Tuning | E standard |
| Guitar controls | Volume approximately 9; tone approximately 7–8 |
| Technique | Medium pick, light palm muting near the bridge, controlled downstrokes, and short releases between chord changes |

## Target character

This patch targets the compact rhythm-guitar sound heard through much of the song rather than attempting to reproduce every layered studio part. It should have audible grain and sustain without becoming a conventional high-gain rock tone.

Compression keeps the muted notes even, while the low-drive booster and Pushed amplifier create the warm, slightly blurred attack. Chorus is concentrated above the low frequencies so the sound moves and widens without making the palm-muted bass strings feel unstable.

The original arrangement becomes broader and dirtier during the choruses. With this single patch, approximate that lift by turning the guitar volume fully up, easing the palm mute, and striking the chords more firmly.

## Signal chain

```text
Input -> Booster: Warm OD -> Mod: Compressor -> Pushed Amp
      -> FX: Chorus -> Channel EQ (Amp Out) -> Noise Suppressor
      -> Volume Pedal -> Reverb: Room -> Output
```

## Amplifier

| Parameter | Value |
| --- | ---: |
| Amp Type | Pushed |
| Variation | Off |
| Gain | 33 |
| Volume | 72 |
| Bass | 44 |
| Middle | 59 |
| Treble | 55 |
| Presence | 47 |
| Contour | Off |
| Cabinet Resonance | Vintage |

The Pushed amp supplies elasticity and mild breakup while leaving space for the booster to shape the attack. Vintage cabinet resonance softens the response and avoids the tight, modern feel of a heavily produced rock tone.

## Effects overview

| Block | On/Off | Type | Primary level/knob | Usage |
| --- | --- | --- | ---: | --- |
| Booster | On | Warm OD | Drive 14 | Main tone |
| Mod | On | Compressor | Level 56 | Main tone |
| FX | On | Chorus | High Level 38 | Main tone |
| Reverb | On | Room | Effect Level 13 | Main tone |

### Booster

| Parameter | Value |
| --- | ---: |
| Type | Warm OD |
| Drive | 14 |
| Tone | -8 |
| Bottom | -6 |
| Effect Level | 48 |
| Solo Sw | Off |
| Solo Level | 50 |
| Direct Mix | 0 |

Warm OD adds soft-edged harmonic density without overwhelming the chord voicings. The reduced Bottom prevents the bridge humbucker and palm-muted notes from making the amplifier feel congested.

### Mod

| Parameter | Value |
| --- | ---: |
| Type | Compressor |
| Compressor Type | Light |
| Sustain | 36 |
| Attack | 55 |
| Level | 56 |
| Tone | -2 |

This is moderate compression intended to stabilize the rhythm and extend chord decay while retaining enough attack to hear the muted picking pattern.

### FX

| Parameter | Value |
| --- | ---: |
| Type | Chorus |
| Low Rate | 18 |
| Low Depth | 22 |
| Low Pre Delay | 8.0 ms |
| Low Level | 24 |
| Direct Mix | 85 |
| High Rate | 24 |
| High Depth | 38 |
| High Pre Delay | 12.0 ms |
| High Level | 38 |
| Crossover Frequency | 800 Hz |

The low band receives relatively little modulation, keeping the rhythm grounded. The deeper high-band chorus supplies the nostalgic width and pitch movement without turning the whole guitar into an exaggerated modulation effect.

### Reverb

| Parameter | Value |
| --- | ---: |
| Type | Room |
| Reverb Time | 1.8 s |
| Pre Delay | 18 ms |
| Effect Level | 13 |
| Direct Mix | 100 |
| Low Cut | 160 Hz |
| High Cut | 6.3 kHz |
| Density | 7 |

The reverb should provide a short studio-like space rather than an obvious ambient tail. Its filtered low end leaves room for the song’s bass and kick.

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
| High-Mid Frequency | 1.6 kHz |
| High-Mid Q | 0.7 |
| High-Mid Gain | +1 dB |
| High Gain | -2 dB |
| Low Cut | 80 Hz |
| High Cut | 8.0 kHz |
| Level | 0 dB |

The broad low-mid reduction prevents the compressed, chorused signal from accumulating too much body. The small 1.6 kHz lift restores chord definition without creating a sharp pick click.

### Noise suppressor

| Parameter | Value |
| --- | ---: |
| On/Off | On |
| Threshold | 20 |
| Release | 60 |

Keep the threshold low enough that sustained chords and the reverb tail decay naturally.

## Playback context

These are practical starting conditions rather than mandatory stored settings.

| Setting | Value |
| --- | --- |
| Power Control | 0.5 W for home practice; Half for rehearsal |
| Master Volume | Start around 10–11 o’clock and adjust for the room |
| Output | Built-in speaker |
| Air Feel | Blend when using Phones, Line Out, or USB |
| Global EQ | Off |
| Room/monitoring notes | Raise the amplifier from the floor if the low mids become boomy; judge the chorus from playing position rather than directly in front of the speaker |

## Playing notes

- Use only enough palm pressure to shorten the notes; fully deadened strings will lose the track’s melodic movement.
- Keep the pick strokes compact and consistent. Let the compressor supply sustain rather than striking every chord harder.
- For verses, retain the light palm mute and keep the guitar volume around 9.
- For choruses, move the volume to 10, relax the mute, and use broader strokes. This approximates the lift supplied by the recording’s additional guitar layers.
- Let prominent chord changes overlap slightly with the chorus modulation, but release pressure between phrases to prevent noise accumulating.
- If the tone feels overly polished, pick slightly closer to the bridge before adding more overdrive.

## Adjust it for your rig

- **Too bright:** Lower Presence to 42 first. If the upper edge remains sharp, change the Channel EQ High Cut to 6.3 kHz.
- **Too dark:** Raise Presence by 3–5 points or move the guitar tone toward 10 before adding Treble.
- **Too loose or bass-heavy:** Lower Bass to 39, change Booster Bottom to -10, or raise the Channel EQ Low Cut to 100 Hz.
- **Too noisy:** Reduce Compressor Sustain before raising the noise-suppressor Threshold in increments of 3–5.
- **Different pickups:** With a single coil, raise Booster Effect Level to approximately 53 and Gain to 36. With a very hot humbucker, reduce Gain to 28–30 and Booster Effect Level to approximately 43.
- **Too clean:** Raise Booster Drive to 18. If more gain is still required, increase amplifier Gain in small steps.
- **Too distorted:** Reduce Booster Drive to 8–10 before lowering amplifier Gain.
- **Chorus sounds seasick:** Lower High Depth to 28 and Low Level to 18.
- **Not enough movement:** Raise High Depth to 44, but leave Low Depth below 28 so the muted low strings remain stable.
- **Chorus section lacks size:** Increase guitar volume to 10 and reduce the palm mute. For recording, double the performance rather than increasing chorus depth excessively.

## References

- [Djo interview — Rolling Stone UK](https://www.rollingstone.co.uk/music/joe-keery-djo-end-of-beginning-tiktok-interview-stranger-things-37380/) — Keery describes the song’s return to analogue instruments and simpler construction after the computer-heavy production used elsewhere on *Decide*.
- [Djo production recreation — Noise Chest](https://noisechest.com/articles/djo-end-of-beginning) — a third-party reconstruction identifying palm-muted, chorused verse guitar and additional distorted guitar layers in the choruses; it is not documentation of the original settings.
- [Joe Keery on *Decide* — W Magazine](https://www.wmagazine.com/culture/joe-keery-djo-decide-new-album-interview) — contemporary interview covering the album’s nostalgic intent and Keery’s stated musical influences.
- [Inside Track: Djo “End Of Beginning” — Sound On Sound](https://www.soundonsound.com/techniques/inside-track-djo-end-beginning) — interview with producer and mix engineer Adam Thein about the song’s production and mix.
- [BOSS Tone Studio for KATANA Gen 3 parameter guide](https://static.roland.com/assets/media/pdf/BTS_KTN3_PC_eng01_W.pdf)
- [BOSS Katana-100 Gen 3 product page](https://www.boss.info/uk/products/katana-100_gen_3/)

## Revision history

| Date | Change |
| --- | --- |
| 2026-08-07 | Removed unused disabled effects and optional settings from the guide. |
| 2026-08-07 | Initial documented settings for the warm, chorused main rhythm sound. |
