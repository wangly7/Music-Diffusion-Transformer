# MuDit

MuDit is a Transformer- and diffusion-based text-to-music generation framework for synthesizing high-quality audio from natural language prompts. The pipeline encodes semantic text representations using pretrained Transformer encoders, conditions a diffusion model to generate mel spectrograms through iterative denoising, and reconstructs realistic waveforms using a HiFi-GAN neural vocoder.

## Architecture

Text Prompt  
→ Transformer Text Encoder (BERT / T5 / CLAP)  
→ Conditional Diffusion Model (U-Net / DiT)  
→ Mel-Spectrogram Generation  
→ HiFi-GAN Vocoder  
→ Audio Waveform

## Features

- Text-conditioned music generation
- Transformer-based semantic prompt encoding
- Diffusion-driven mel-spectrogram synthesis
- High-fidelity neural vocoding with HiFi-GAN
- Modular PyTorch training and inference pipeline

## Goal

This project explores efficient and controllable music generation by modeling mel spectrograms with conditional diffusion instead of directly generating raw waveforms.