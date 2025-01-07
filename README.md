# MEI-GMD
MEI transcriptions (Agostini notation) of the MIDI files from the [Groove MIDI Dataset](https://magenta.tensorflow.org/datasets/groove)  (GMD v.1.0.0-midionly in [https://magenta.tensorflow.org/datasets/groove](https://magenta.tensorflow.org/datasets/groove)).

The MIDI files of the GMD are captation of human performances of professional or semi-professional drummers on an electronic drum kit ROLAND T-11.

They have been processed with the tool qparse/TSM (Tree Score Model) for MIDI-to-score transcription, extended with specific classes for the parsing e-drum kit MIDI files and for post-processing the transcription results.

- for the C++ code of qparse/TSM, see https://gitlab.inria.fr/qparse, branch `partial`
- the code of a Python binding (based on [pybind11](https://github.com/pybind/pybind11)) can be found in the same repository.
- a Python script for processing GMD with the above tool is available at in https://gitlab.inria.fr/transcription/gmd-transcript/-/blob/main/scripts



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

info on the MIDI keys mapping for the [Roland TD-11](https://www.roland.com/global/products/td-11k/) MIDI drum kit  used to record the MIDI performances in GMD.
It uses some pitch values that differ from the General MIDI (GM) Specifications. 

see also https://magenta.tensorflow.org/datasets/groove#drum-mapping



### metadata 

txt file from the GMD `info.cvs`


