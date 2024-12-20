# MEI-GMD
MEI transcriptions of the MIDI files from the [Groove MIDI Dataset](https://magenta.tensorflow.org/datasets/groove)  (GMD)

Groove MIDI dataset v.1.0.0 midionly in [https://magenta.tensorflow.org/datasets/groove](https://magenta.tensorflow.org/datasets/groove)



THE REFERENCE TO TOOLS USED FOR TRANSCRIPTION HEVE BEEN HIDDEN DUE TO ANONYMITY RESTRICTIONS



### directory `DiSj_n` 

every directory of the form `DiSj_n` corresponds to the GMD entry for:

- drummer `i`  
- session `j`  
- MIDI file `n`  

### MIDI file names

they are the same as in GMD

```
n_genre_tempo_beatorfill_ts.mid
```

- `n` is the `n` in directory name
- genre in 
- tempo in bpm
- `beatorfill` = `beat` or `fill`
- `ts` = time signature, in general `4-4`



### directory `schemas`

it contains the tree grammar files defining the output syntax for parsing the MIDI files.



### file `mapping.md`

info on the MIDI keys mapping for the 
[Roland TD-11](https://www.roland.com/global/products/td-11k/) MIDI drum kit 
used to record the MIDI performances in GMD.
It uses some pitch values that differ from the General MIDI (GM) Specifications. 

see also https://magenta.tensorflow.org/datasets/groove#drum-mapping



### metadata 

txt file from the GMD `info.cvs`



