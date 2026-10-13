# Speech Emotion Recognition

A Python machine learning project that predicts **calm, happy, fearful, and disgust** emotions from recorded speech using librosa and scikit-learn.

## How It Works

- Downloads the RAVDESS dataset using KaggleHub.
- Extracts 180 audio features: MFCC, chroma, and Mel spectrogram features.
- Trains a Multi-Layer Perceptron (MLP) classifier to predict emotions.

## Getting Started

Install the required libraries:

```bash
pip install librosa soundfile numpy scikit-learn kagglehub jupyter
```

Open the project notebook in Jupyter and run the cells in order. The notebook downloads the dataset automatically, extracts features, trains the model, and displays test accuracy.

## Results

| Metric | Result |
| --- | --- |
| Training samples | 576 |
| Testing samples | 192 |
| Features per sample | 180 |
| Reported test accuracy | 66.67% |

Results may vary between training runs. This is an educational project evaluated on recorded dataset audio; real-world performance has not been measured.

## Dataset and Credits

- Dataset: [RAVDESS on Kaggle](https://www.kaggle.com/datasets/orvile/ravdess-dataset)
- Implementation adapted from the DataFlair Speech Emotion Recognition tutorial.

