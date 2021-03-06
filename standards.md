# Standards

- Drum samples should be recorded as loud as possible, around `0db`. When configured on a track, they should be played back at around `-7.8db`.
- Synth samples are more flexible, when they're played back on a track they should be around `-2db`.

## MIDI

- MIDI notes should have a velocity of `100` by default, at `100` velocity, a drum sample should be at `-7.8db`.

### MIDI Setup

1. Start all notes at velocity 100 with appropriate levels for all sounds at that velocity (e.g., `-8db` for drum sounds).
2. Mix by adjusting the velocity of each sound.

### Velocity Modulation

- If a note has a volume of `-8db` at 100 velocity, it should be `-4db` at 127 velocity.
