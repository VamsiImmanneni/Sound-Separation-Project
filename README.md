# Multi-Pitch Detection Project

## Daniel Shu, Vamsi Immanneni

## Sound Files
This is a directory containing recordings of piano chords.
Here, folders contain the separate chords themselves, while the other files
contain the raw recordings with many chords in them at once. Below is an example of
how we can select a .wav file, and if run, it plays the sound in it.

```python
from pydub import AudioSegment
audio = AudioSegment.from_wav('Sound_Files/C_Fourth_Octave/A3C4.wav')
```

## Graphs
This is a folder that stores some of our generated graphs. 

## Analysis-Midway
This is the first Python Notebook we created. Here is a lot of scratchwork we did when experimenting
with FFT, STFT, and some model creation. 