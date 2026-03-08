# 🎨 Chromesthesia Chord Engine

### Visualizing Music Through Chords and Colors

## Project Overview

Inspired by the fascinating phenomenon of **chromesthesia**—where individuals _see_ colors when they hear music—this project provides a unique way to experience sound visually.

The **Chromesthesia Chord Engine** analyzes musical audio, detects chord progressions, and translates those chords into dynamic visual representations using colors and shapes. This allows users to literally **see the emotional landscape of music** as it plays.

Developed for a **Data Science class**, this project bridges music composition, audio analysis, and machine learning to create a tool that is both technically innovative and personally expressive.

<p align="center">
	<a href="demo.mp4">
		<img src="docs/demo-preview.gif" alt="Watch demo" width="420" />
	</a>
</p>

<p align="center">Click to watch demo</p>

---

## How It Works

The system processes audio input and follows these steps:

1. Extracts audio features relevant to harmony and pitch
2. Uses a trained machine learning model to predict chords
3. Maps predicted chords to a custom color and shape palette
4. Animates visuals in real time or generates a synchronized video output

---

## Key Highlights

### 🎼 Chord Detection

- Uses **chroma-based audio features** to accurately detect chord progressions in music tracks.

### 🌈 Dynamic Visualization

- Translates detected chords into an engaging visual experience using a custom-designed **color and shape mapping**.

### 🧪 Programmatically Generated Dataset

- Trained on **synthetic chord audio samples**, enabling precise control over chord labels and data balance.

---

## Technical Details

### Dataset

- Programmatically generated **synthetic chord audio**
- Covers a wide range of **major and minor triads**

### Algorithm

- **Convolutional Neural Network (CNN)** for chord classification
- Operates on **mel-spectrogram features**
- Replaced an initially considered **Random Forest Classifier** for improved accuracy and pattern recognition

### Tools & Libraries

- **Google Colab**
- **Python**
- `librosa` – audio analysis & feature extraction
- `scikit-learn` – data preprocessing (`LabelEncoder`, `train_test_split`)
- `tensorflow` – CNN model training
- `matplotlib` – visualization utilities
- `soundfile` – audio I/O
- `moviepy` – video generation
- `Pillow` – image manipulation

### Techniques Used

- Audio synthesis
- Mel-spectrogram feature extraction
- CNN training and evaluation
- Dynamic video generation for visual output

---

## Getting Started

### Installation

Set up a Python environment (Google Colab recommended) and install dependencies:

```bash
pip install tensorflow librosa scikit-learn matplotlib numpy soundfile moviepy pillow
```
