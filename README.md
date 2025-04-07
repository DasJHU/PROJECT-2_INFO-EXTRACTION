# PROJECT-2_INFO-EXTRACTION

This repository contains two implementations of Hidden Markov Model (HMM) based systems, one is a basic primary HMM system and the other is a contrastive hmm system with validation testing.

Basic HMM Recognizer
Single HMM for each letter (left-to-right topology)

Special state silence HMM

Baum-Welch training algorithm

Forward-backward algorithm in log-space

Simple likelihood-based decoding

Contrastive HMM:
✅ All basic version features plus:
✅ 80-20 train-validation split
✅ Early stopping with patience=2
✅ Two-phase training
✅ Model checkpointing
✅ Top-3 predictions tracking
✅ Detailed confidence scoring
✅ Automatic results logging
