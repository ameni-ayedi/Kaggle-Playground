## 🧠 Overview

The goal of this project is to **predict the beats-per-minute (BPM)** of songs using various audio and metadata features.  
This task comes from a **machine learning competition** where participants build regression models to estimate the tempo of a track based on the provided dataset.

Accurate BPM prediction can help in **music recommendation**, **genre classification**, and **playlist generation** by understanding a song’s rhythmic characteristics.

## 🧩 Dataset

The dataset consists of various **audio and metadata features** for each song.  
The goal is to predict the **BeatsPerMinute** column (the target variable).

| Column | Description |
|:--|:--|
| `id` | Unique identifier for each song |
| `RhythmScore` | Quantitative measure of rhythmic regularity and beat clarity |
| `AudioLoudness` | Overall loudness level of the track |
| `VocalContent` | Proportion of vocals relative to instrumental parts |
| `AcousticQuality` | Measure of how acoustic (or electronic) the track sounds |
| `InstrumentalScore` | Degree of instrumental richness in the song |
| `LivePerformanceLikelihood` | Probability that the song was recorded live |
| `MoodScore` | Numerical representation of the mood |
| `TrackDurationMs` | Duration of the track in milliseconds |
| `Energy` | Perceived energy or intensity of the song |
| `BeatsPerMinute` | the tempo of the song in BPM (**Target variable**) |
