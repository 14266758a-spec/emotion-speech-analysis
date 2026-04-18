Data

This project uses the IEMOCAP dataset.

Dataset:
IEMOCAP – Interactive Emotional Dyadic Motion Capture Database

Due to licensing restrictions, the dataset is not included in this repository.
Researchers must request access separately.
## Results

The performance of three models was evaluated: text-only, audio-only, and a combined multimodal model.

| Model | Accuracy | Weighted F1-score |
|------|--------|------------------|
| Text-only (TF-IDF) | 0.60 | 0.59 |
| Audio-only (MFCCs) | 0.60 | 0.56 |
| Combined (Multimodal) | **0.66** | **0.65** |

The combined model achieved the highest performance, demonstrating that integrating lexical and acoustic features improves emotion recognition.

### Key Findings
- Multimodal fusion improves accuracy by approximately 6%
- Audio features are more informative than text for certain emotions (e.g., anger)
- Happiness is the most difficult emotion to classify, often confused with neutral
