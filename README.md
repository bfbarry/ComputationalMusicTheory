# Computational Music Theory

Investigating mathematical properties of harmony, and maybe make a music recommendor algorithm out of it

IDEAS:
- implement chroma vector
- Wave properties of certain chords: can we understand why chord progressions sound nice?
- chord graph
- Given a random chord, what is its hamming distance from a nice, normal chord?
    - Like how many steps do you have to take to get to a nice chord?
    - How does this differ depending on the number of notes? (2 notes will always be "nice")  What about the range on the keyboard?
    - How does it differ depending on the "leniency": types of chords allowed in comparison?  Hamming distance will probably be less for complex jazz chords
    - Under what conditions is the hamming distance from different chords the same?
    - What about hamming distance of wave decomposition?
    - Extent to what 'nice' sounds like
        -some jazz chords sound harsh
    - find probability distribution of this number
- Chords often fuse into each other (circle of fifths), how to account for that?
- It would be cool to visualize harmony with color
- How to make make_chord account for combined chords (e.g. dim 7)
- Need a chord identifier as well as maker
- Can we quantify harmony using waveform shape?
- Fourier stuff for chord decomposition

Resources:
- [This audio signal processing lib](https://madmom.readthedocs.io/en/latest/introduction.html)
- ['Structured Prediction Models for Chord Transcription of Music Audio'](https://www.ee.columbia.edu/~dpwe/pubs/WellEJ09-chords.pdf)
- ['Generating music in the waveform domain'](https://benanne.github.io/2020/03/24/audio-generation.html)
- "Chord detection using deep learning" (Zhou, Lerch)
- "Chroma Feature Extraction" 
- "Neural Networks for Musical Chord Identification"