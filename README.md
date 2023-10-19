# Music-Genre-Classification
How can we classify music into different genres using deep learning techniques?

## Introduction
This project aims to classify music genres using deep learning. By analyzing short music clips, we can derive patterns and features to categorize them into specific genres. The approach is particularly beneficial for streaming platforms, music databases, and artists.

## Why Deep Learning?
Deep learning offers several advantages for music genre classification:
- Efficiently handles large datasets.
- Automatically learns intricate features.
- Captures layered musical complexity.
- Benefits from transfer learning.
- Offers end-to-end learning capabilities.

## Dataset
The dataset consists of audio samples segmented into training, validation, and test sets. Each audio sample has features like melgrams and MFCCs contained in the `X.npy` files. The corresponding genres are in the `labels.npy` files.

## Approach
- **Short Music Clips:** The model identifies genre-defining characteristics from 1-second audio clips.
- **Feature Extraction:** Uses Mel-frequency cepstral coefficients (MFCCs) for Feedforward Neural Networks and mel spectrograms for CNNs.
- **Deep Learning Models:** The project employs Feedforward Neural Networks and Convolutional Neural Networks (CNNs) to process MFCCs and mel spectrograms, respectively.

## Conclusion
The project exemplifies the power of deep learning in processing and understanding complex audio data. By using MFCCs and mel spectrograms, the model captures essential audio features and learns patterns indicative of specific music genres.

