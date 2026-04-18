# emotion-speech-analysis

This project investigates how emotional information in speech is conveyed through both acoustic features and linguistic transcripts.

## Dataset

Interactive Emotional Dyadic Motion Capture Database (IEMOCAP)

The dataset includes:
- audio recordings  
- transcriptions  
- emotion annotations  

A subset of approximately 4,489 utterances was used for analysis.

---

## Research Question

How does combining acoustic information and transcript information influence emotion recognition across emotion categories?

---

## Methods

- Text features: TF-IDF (unigrams + bigrams)  
- Audio features: MFCCs, energy, zero-crossing rate (librosa)  
- Models: Logistic Regression  

---

## Experiments

Three models were implemented:

1. Text-only model  
2. Audio-only model  
3. Combined model (text + audio)  

---

## Results

| Model | Accuracy |
|------|--------|
| Text-only | 0.43 |
| Audio-only | 0.53 |
| Combined | **0.60** |

The combined model achieved the highest performance, demonstrating that integrating acoustic and lexical features improves emotion recognition.

---

## Key Findings

- Multimodal fusion improves performance over single-modality models  
- Audio features are more informative than text for certain emotions (e.g., anger)  
- Happiness is the most difficult emotion to classify and is often confused with neutral  
- Performance differences across models were statistically significant  

---

## Statistical Analysis

- One-way ANOVA showed a significant effect of model type  
- p-value = 0.004, indicating differences between models are statistically significant  

---

## Current Status

- Data parsed and cleaned  
- Features extracted from text and audio  
- Models trained and evaluated  
- Statistical analysis completed  
- Error analysis conducted using confusion matrix  


