# Multispeaker, adaptive TTS for Portuguese
In this project we implement a neural multispeaker end-to-end TTS system for Portuguese.

The overall system is composed of three parts:
* a speaker encoder trained on Portuguese database composed of 1434 speakers
* a text-to-spectrogram inverter (Tacotron)
* a neural vocoder (Hifi-GAN) to convert spectrograms into speech
