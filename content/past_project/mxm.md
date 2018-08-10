---
title: "MxM"
github: "mxm"
website: "https://github.com/MusicExMachina/Impromptu"
---

What is MxM? MxM (Music ex Machina) is a music machine learning project which will create new music based on the stylistic decisions of training input. Ideally, if one fed in passages written by Bach, the output would be indistinguishable from Bach. If one fed in Debussy, the output would be indistinguishable from Debussy.

How does MxM work? More concretely, Our current plan is to use two, independent LSTM RNNs (Long Short-Term Memory Recurrent Neural Networks). We will at first generate our own input from scratch, but will soon move to accepting the ever-popular MIDI file in order to more easily accept new input.

Why use MxM? MxM has many potential consumers, ranging from listeners to musicians themselves. Game developers could even utilize MxM for their own games, to generate music indefinitely in the background, and- potentially- modifying it to match gameplay. It would be possible, for instance, to make intense moments in gameplay intense musically (by using node weights trained off of intense music).
