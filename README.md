# POS tagging using modified Viterbi

## Problem Statement

In this assignment, we need to Modify the Viterbi algorithm to solve the problem of unknown words using at least two techniques.
Compare the tagging accuracy after making these modifications with the vanilla Viterbi algorithm.
List down at least three cases from the sample test file (i.e. unknown word-tag pairs) which were incorrectly tagged by the original Viterbi POS tagger and got corrected after your modifications.

## Solution

### Technique I: Using transition probability of tags when emission probability is zero because of unknown words
### Technique II: Using bigram backed up by the rule based tagger for unknown words
