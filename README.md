# Speech Processing & Recognition Lab Work

This repository contains 8 practical programs implementing fundamental speech processing and recognition techniques.

## Programs Overview

### Program 1: Speech Signal Sampling and Reconstruction
- Loaded and visualized real speech signal in time domain
- Downsampled to 8kHz, 16kHz, and 44.1kHz sampling rates
- Reconstructed using Zero-Order Hold and Linear Interpolation methods
- Generated synthetic speech using source-filter model (glottal pulse + white noise)
- Calculated and compared MSE for different sampling rates and methods
- Found Linear Interpolation performs better than Zero-Order Hold

**Screenshot**

---

### Program 2: Fourier Transform Analysis
- Generated and analyzed four signal types: Sinusoidal, Composite, Exponentially Decaying, Rectangular
- Computed both DTFT (continuous frequency) and DFT (discrete frequency)
- Compared time-domain vs frequency-domain representations
- Showed how different signals appear in frequency spectrum

**Screenshot Placeholder**

---

### Program 3: Real-time Speech Recognition
- Implemented microphone-based speech-to-text conversion
- Integrated Google Speech Recognition API
- Added ambient noise adjustment for better accuracy
- Implemented timeout and error handling
- Successfully recognized spoken phrase "hello my name is Ismail Basheer"

**Screenshot Placeholder**

---

### Program 4: Linear Predictive Coding (LPC)
- Implemented LPC algorithm using Levinson-Durbin recursion
- Extracted vocal tract coefficients from speech signal
- Reconstructed speech from LPC coefficients
- Estimated formant frequencies for vowel identification
- Compared with known vowel formant values
- Visualized frequency response of vocal tract filter

**Screenshot Placeholder**

---

### Program 5: Linear Time Normalization
- Applied time normalization to align speech signals of different durations
- Used linear interpolation to match signal lengths
- Computed alignment path between reference and test signals
- Visualized aligned signals showing amplitude differences
- Demonstrated timing normalization while preserving signal features

**Screenshot Placeholder**

---

### Program 6: Dynamic Time Warping (DTW)
- Implemented DTW algorithm for sequence alignment
- Created cost matrix and found optimal warping path
- Visualized accumulated cost matrix with warping path
- Calculated DTW distance (3.0) indicating high similarity
- Demonstrated alignment of sequences with different lengths

**Screenshot Placeholder**

---

### Program 7: Hidden Markov Model (HMM)
- Implemented HMM for phoneme sequence generation
- Defined phonemes: /s/, /p/, /ie:/, /tʃ/ with probabilities
- Created transition and emission probability matrices
- Generated random phoneme and observation sequences
- Showed probabilistic state transitions in speech

**Screenshot Placeholder**

---

### Program 8: Viterbi Algorithm
- Implemented Viterbi algorithm for decoding hidden states
- Applied to recognize word "hello" phonemes: /h/, /e/, /l/, /o/
- Used HMM with transition and emission probabilities
- Found most likely phoneme sequence from observations
- Computed probability of decoded path (0.03704)
- Successfully decoded "hello" from acoustic features

**Screenshot Placeholder**

## Technical Requirements
- Python 3.x
- Libraries: librosa, numpy, scipy, matplotlib, speechrecognition, scikit-learn

## Usage
```bash
pip install -r requirements.txt
# Run individual programs as needed
```
