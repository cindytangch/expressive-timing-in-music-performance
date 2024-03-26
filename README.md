# Expressive Timing in Music Performance

This study is a part of the DH-401 Digital musicology course at EPFL.

In this work we explore the distortion of the metrical grid in human performance, by finding a interesting mapping from symbolic time to real time.

## Dataset

The data utilized is sourced from the [Aligned Scores and Performances (ASAP) dataset](https://github.com/fosfrancesco/asap-dataset), which comprises aligned musical scores in both MIDI and MusicXML formats, alongside corresponding performances in audio and MIDI formats. Each entry in the dataset is annotated with downbeat, beat, time signature, and key signature information.

For our analysis, we choose to focus on the [Mozart's Piano Sonatas](https://github.com/fosfrancesco/asap-dataset/tree/master/Mozart/Piano_Sonatas) subcorpus.

## Instructions
Task A (The timing function):
- Implement a function timing that maps symbolic time to performance attributes (tempo,velocity), so that one can use it to transform the "unperformed" MIDI to the "performed" MIDI.
  - Plot this function as a tempo curve that happens in time.
  - (Optional) Plot this function as a velocity curve that happens in time.

Task B (Empirical findings):
- Choose one subcorpus (for example Bach Preludes) and do the following analyses:
  - What is the distribution of note onsets on metrical locations? Answer this question separately for different time signatures. At least do 4/4 and 3/4 time signatures. Illustrate your finding with figures.
  - Where in the metrical grid are expressive timing likely to happen? Support it with quantitative evidence. Illustrate your finding with figures.
- Think about another empirical question that you can verify from this data, and present your findings.
  - (Easy example) which style has the most variability in timing.
  - (Difficult example) How well can your model generalize across different styles?


## Credits
Authors: Romane Clerc - Octavio Profeta - Cindy Tang - Shu Yang

Professor: Martin Rohrmeier

Course: DH-401 Digital musicology, EPFL

Date: 27.03.2024
