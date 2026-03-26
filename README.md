# emotion-speech-analysis
This project investigates how emotional information in speech is conveyed through both acoustic features and linguistic transcripts.
## Dataset
Interactive Emotional Dyadic Motion Capture Database (IEMOCAP)

The dataset includes:
- audio recordings
- transcriptions
- emotion annotations
- Subset of ~500 samples used for modeling
## Research Question
How does combining acoustic information and transcript information influence emotion recognition across emotion categories?

## Methods

* Text features: TF-IDF (unigrams + bigrams)
* Audio features: MFCCs, energy, zero-crossing rate (librosa)
* Models: Logistic Regression

## Experiments

Three models were implemented:

1. Text-only model
2. Audio-only model
3. Combined model (text + audio)

## Results

* Text model accuracy: 43%
* Audio model accuracy: 53%
* Combined model accuracy: 60%

## Statistical Testing

* McNemar’s test used to compare models
* Result: p = 0.0045 (significant improvement)

## Current Status

* Data parsed and cleaned
* Features extracted
* Models trained and evaluated
* Statistical comparison completed

## Next Steps

* Improve feature representation
* Expand dataset
* Refine analysis

