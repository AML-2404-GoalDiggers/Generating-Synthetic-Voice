# Generating-Synthetic-Voice

Our project describes a neural network-based system for text-to-speech(TTS) synthesis that is able to generate speech audio in the voice of different speakers, including those unseen during training. Dataset will include noisy speech without transcripts from thousands of speakers. Our model will consist of three independent neural networks: a speaker encoder, a synthesizer and a vocoder. The goal of this work is to build aTTS system which can generate natural speech for a variety of different speakers in a data efficient manner.

This repo is an implementation of SV2TTS (Trasfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis) with a vocoder that works in real-time.

We created a demo toolbox which can be run in a virtual environment which takes 4 utterances of recordings either loaded from dataset given or recorded in real-time and generates mel spectrum waveforms using encoder, synthesizer and vocoder.

The result produced is a cloned voice in voice of a speaker from the dataset or the speaker who records the voice.

The dataset which we have created has been uploaded in the repository
The model is trained on Librispeech dataset. Link: http://www.openslr.org/12/

The working demonstration of our project is provided namely 'Generating Synthetic Voice working demonstration' video file.
