# Drum codes
mapping of MIDI keys into note names
in Agostini and Universal Drum Notations 
for Roland and GM instruments

cf. https://magenta.tensorflow.org/datasets/groove

| MIDI | note Agostini | note US | Roland | GM   | DrumCode |
|------|---------|---------|-------|--------|----------|
| 36 | D4 (*62*) | F4 (*65*) | Kick   | Bass  | `BD` |
| 38 | B4 (*71*) | C5 (*72*) | Snare Head | Ac. Snare | `SD` |
| 40 | B4/ (*71*) | C5 (*72*) | Snare Rim  | El. Snare | `SDR` |
| 37 | B4x (*71*) | C5x (*72*) | Snare X-Stick | Side Stick | `SDX` |
| 48 | E5 (*76*) | E5 (*76*) | Tom 1 | Hi-Mid Tom | `TH` |
| 50 | E5/ (*76*) | E5 (*76*) | Tom 1 Rim | Hi Tom | `THR` |
| 45 | C5 (*72*) | D5 (*74*) | Tom 2 | Low Tom | `TM` |
| 47 | C5/ (*72*) | D5 (*74*) | Tom 2 Rim | Low-Mid Tom | `TMR` |
| 43 | F4 (*65*) | A4 (*69*) | Tom 3 Head | High Floor Tom | `TF` |
| 58 | F4/ (*65*) | A4 (*69*) | Tom 3 Rim  | Vibraslap | `TFR` |
| 46 | G5ⓧ (*79*) | G5ⓧ (*79*) | HH Open Bow | Open HH  | `HHO` |
| 26 | G5ⓧ (*79*) | G5ⓧ (*79*) | HH Open Edge | N/A | `HHO` (*) |
| 42 | G5x (*79*) | G5x (*79*) | HH Closed Bow | Closed HH  | `HHC` |
| 22 | G5x (*79*) | G5x (*79*) | HH Closed Edge | N/A | `HHC` (*) |
| 44 | B3ⓧ / x (*59*) | D4x (*62*) | HH Pedal | id. | `HHP` |
| 49 | C6x (*84*) | A5x (*81*) | Crash 1 Bow | Crash Cymbal 1 | `C1B` |
| 55 | B5x (*83*) | B5x (*83*) | Crash 1 Edge | Splash Cymbal | `C1E` |
| 57 | D6x ? (*86*) | C6x ? (*84*) | Crash 2 Bow | Crash Cymbal 2 | `C2B` |
| 52 | C6ⓧ (*84*) | B5ⓧ (*83*) | Crash 2 Edge | Chinese Cymbal | `C2E` |
| 51 | A5x (*81*) | F5x (*77*) | Ride Bow | Ride Cymbal 1 | `RB` |
| 59 | A5ⓧ (*81*) | F5ⓧ (*77*) | Ride Edge | Ride Cymbal 2 | `RE` |
| 53 | A5◇ ? (*81*) | F5◆ ?  (*77*) | Ride Bell | Ride Bell | `RC` |

- bow (cymbal or HH) = stick on the part between the edge and the bell – the largest surface. 

- HH Pedal: difference de notation Agostini pour
  - Open HH Pedal = B3ⓧ
  - Closed HH Pedal = B3x

- cow bell = A5▾ (Agostini) or B5▾ (US)
