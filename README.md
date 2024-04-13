# Spanish Part-of-Speech Tagger using Hidden Markov Models (HMM)

## Overview:

This repository contains Python code for implementing a part-of-speech (POS) tagger based on Hidden Markov Models (HMM) and applying it to perform morphosyntactic tagging of Spanish sentences. The tagger is trained on a labeled corpus, and the Viterbi algorithm is used to determine the most likely sequence of tags for a given input sentence.


## Key Steps:

1. **Training the HMM:**
   - The HMM is trained on the labeled corpus provided (`corpus-tagged.txt`).
   - Probability tables for emission and transition probabilities are constructed based on the corpus data.

2. **Viterbi Algorithm:**
   - The Viterbi algorithm is employed to determine the most likely sequence of POS tags for a given input sentence.
   - The algorithm calculates the probability of each possible tag sequence, considering both emission and transition probabilities.

3. **Morphosyntactic Tagging:**
   - The trained POS tagger is used to perform morphosyntactic tagging of a given sentence.
   - The Viterbi algorithm is applied to determine the most probable sequence of POS tags for the input sentence.

