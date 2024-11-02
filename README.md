## Word Trigger Detection Model 🔊🗣️
This project is a deep learning-based model for detecting specific keywords or phrases within audio files. It leverages spectrogram analysis and neural networks to identify trigger words in real-time or recorded audio data.Data
## Dataset
The dataset consists of:

- Activates: Audio clips containing the trigger word.
- Negatives: Clips without the trigger word.
- Backgrounds: Background sounds for a more realistic audio environment.

<a href ="https://drive.google.com/drive/folders/14dmwPMM0OSHBQXRYR6Bl4Cg7H61rRTOm?usp=sharing"> Dataset</a>


## Model
This model uses a combination of Convolutional and LSTM layers to detect trigger words:

- Spectrogram Analysis: The audio data is transformed into spectrograms for visual representation.
- Convolutional Layer: Captures spatial features in the spectrogram.
- LSTM Layer: Models sequential dependencies in the audio data.
- Dense Output Layer: Provides binary output indicating the presence of the trigger word.
