# Instrumental-Causal-Learning
This repository archives the code used for the paper "Instrumental Causal Learning".

## Base Epistemic and Instrumental Casual Learning Models
The WebPPL code used to compute the posteriors for the base epistemic and instrumental causal learning models can be found in the "icl-model-base.txt" file. This code outputs the posteriors (and confidence intervals) for both models. The observations can be modified to fit different learning scenarios (e.g., "two-event", "three-event", "repeated-event", "varied-event", and "uniintentional-event" described in the paper).

## Epistemic and Instrumental Models Assuming Intentionality
The WebPPL code used to compute the posteriors for the "epistemic + intentionality" and "instrumental + intentionality" causal learning models can be found in the "icl-model-intentionality.txt" file. This code was used only for the "intentional-event" condition described in the paper.

## Bayes Factors Computations
The WebPPL code used to compute the Bayes Factors to compare different models can be found in "bayes-factor-base.txt" and "bayes-factor-intentionality.txt". The code in these 2 files are similar. However, "bayes-factor-base.txt" was used to compare between the Epistemic and Instrumental Learning Models (Studies 1-3) while "bayes-factor-intentionality.txt" was used to compare models assuming intentionality against their respective baseline models (Study 4). 
