# Keyword Detection

This repository contains a keyword detection system.

The trigger word will be "activate." Every time it hears "activate," it will emit a sound.

When a representation of audio is presented, it can be difficult to discern whether the word "activate" was said.
To make the sequence model more easily learn trigger words,  compute a spectrogram of the audio.A spectrogram shows us how many different frequencies are present in an audio clip at any given moment.

##### GRU (Gated Recurrent Unit) detects when someone has finished saying "activate."

## Model
The model will use four 1-D convolutional layers, two GRU layers, and one dense layer.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pydub and tdutils.

```bash
pip install pydub
pip install tdutils
```
## Language
The code is written in python(keras).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
