# Text-to-Voice Generator

This Python script demonstrates a text-to-voice generator using the Tacotron 2 model, an advanced machine learning-based text-to-speech synthesis model. The Tacotron 2 model can convert input text into natural-sounding speech.

## Prerequisites

- Python 3.7 or higher
- TensorFlow (version 2.11.0)
- NumPy (version 1.24.2)
- Librosa (version 0.10.0)
- Matplotlib (version 3.7.1)
- SciPy (version 1.11.0)
- SoundDevice (version 0.4.6)

## Installation

1. Clone the repository or download the code files.
2. Install the required Python packages using the following command:

```shell
pip install tensorflow numpy librosa matplotlib scipy sounddevice
```

## Usage

1. Make sure you have the pre-trained Tacotron 2 model file available. Replace `'path/to/tacotron2/model'` in the code with the actual path to the saved model file.

2. Implement or use a pre-trained model/library for text-to-phoneme conversion in the `text_to_sequence()` function. This function should convert the input text into a sequence of phoneme IDs.

3. Run the script using the following command:

```shell
python text-to-voice.py
```

4. Provide input text when prompted. For example, you can type `"Hello, how are you?"`.

5. The script will generate a WAV file named `output.wav` containing the synthesized speech.

6. The generated audio can also be played using the `sounddevice` library.

## Customization

- If you have a different pre-trained model, update the code to load the correct model file and adjust any necessary parameters.

- Modify the `text_to_sequence()` function to use your own logic or another pre-trained model/library for text-to-phoneme conversion.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The text-to-voice generator is based on the Tacotron 2 model, developed by researchers at Google. For more information about Tacotron 2, refer to the following papers:

- [Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions](https://arxiv.org/abs/1712.05884)
- [Tacotron 2: Generating Human-like Speech from Text](https://arxiv.org/abs/1712.05884)

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## Authors

- [Abhin](https://github.com/dearabhin)

## References

- [Tacotron 2 GitHub Repository](https://github.com/dearabhin/text-to-voice-generator)

## Disclaimer

This project is for educational purposes and may require additional setup, training, or fine-tuning to work with specific text-to-speech models or datasets.
