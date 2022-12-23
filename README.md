# Tacotron2-HiFi-GAN-TTS


Implementation of [Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions](https://arxiv.org/abs/1712.05884)

Pretrained HiFi-GAN used for inference taken from: https://github.com/jik876/hifi-gan

Observations: The official implementation uses a few tricks that are not described in the official paper, with the help of which the model learns in a much better. The two most important ones are the multi-step additive convolutional attention and its method of injection into the two decoding LSTM layers.

Feel free to contact me if you need the preprocessed LJSpeech dataset or other any information or would like to use the code.

All rights reserved.
