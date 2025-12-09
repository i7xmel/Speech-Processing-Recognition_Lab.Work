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
<img width="515" height="464" alt="image" src="https://github.com/user-attachments/assets/e62028fb-2eae-4c19-bead-941afcaf565a" />
<img width="807" height="384" alt="image" src="https://github.com/user-attachments/assets/4ec3e27e-2358-4f04-944a-9a2d254f9b39" />
<img width="792" height="594" alt="image" src="https://github.com/user-attachments/assets/7566c2ce-4a2a-4239-b125-d34959229fc2" />



---

### Program 2: Fourier Transform Analysis
- Generated and analyzed four signal types: Sinusoidal, Composite, Exponentially Decaying, Rectangular
- Computed both DTFT (continuous frequency) and DFT (discrete frequency)
- Compared time-domain vs frequency-domain representations
- Showed how different signals appear in frequency spectrum

**Screenshot**
<img width="796" height="347" alt="image" src="https://github.com/user-attachments/assets/f4af7e7a-3325-4e9b-ba28-fb9354c8458d" />
<img width="767" height="352" alt="image" src="https://github.com/user-attachments/assets/34cc3c98-fde9-4425-bd1c-6f0ab1418a90" />
<img width="825" height="394" alt="image" src="https://github.com/user-attachments/assets/5a9b52da-4f43-4eed-bf96-cb54932783fb" />
<img width="793" height="358" alt="image" src="https://github.com/user-attachments/assets/05a7d8c7-7fc5-46d9-ab2b-e62e4e78a873" />


---

### Program 3: Real-time Speech Recognition
- Implemented microphone-based speech-to-text conversion
- Integrated Google Speech Recognition API
- Added ambient noise adjustment for better accuracy
- Implemented timeout and error handling
- Successfully recognized spoken phrase "hello my name is Ismail Basheer"

**Screenshot**
<img width="695" height="162" alt="image" src="https://github.com/user-attachments/assets/28b918b2-49f6-49c2-b940-1b25ad2c672c" />


---

### Program 4: Linear Predictive Coding (LPC)
- Implemented LPC algorithm using Levinson-Durbin recursion
- Extracted vocal tract coefficients from speech signal
- Reconstructed speech from LPC coefficients
- Estimated formant frequencies for vowel identification
- Compared with known vowel formant values
- Visualized frequency response of vocal tract filter

**Screenshot**
<img width="803" height="418" alt="image" src="https://github.com/user-attachments/assets/8e129bea-0163-4638-bce0-0ad15d21ec9d" />
<img width="810" height="502" alt="image" src="https://github.com/user-attachments/assets/39cb312e-8908-4d5b-94c4-d178615a1519" />

---

### Program 5: Linear Time Normalization
- Applied time normalization to align speech signals of different durations
- Used linear interpolation to match signal lengths
- Computed alignment path between reference and test signals
- Visualized aligned signals showing amplitude differences
- Demonstrated timing normalization while preserving signal features

**Screenshot**
<img width="814" height="450" alt="image" src="https://github.com/user-attachments/assets/a6ddd145-3ee4-435f-beb7-0fbc5eb6c33e" />
<img width="836" height="438" alt="image" src="https://github.com/user-attachments/assets/185365d7-ce1f-4853-9210-c26f34af50b8" />


---

### Program 6: Dynamic Time Warping (DTW)
- Implemented DTW algorithm for sequence alignment
- Created cost matrix and found optimal warping path
- Visualized accumulated cost matrix with warping path
- Calculated DTW distance (3.0) indicating high similarity
- Demonstrated alignment of sequences with different lengths

**Screenshot**
<img width="797" height="562" alt="image" src="https://github.com/user-attachments/assets/3bf79753-a4b9-4dcb-96ee-30c6f3b7414a" />
<img width="810" height="755" alt="image" src="https://github.com/user-attachments/assets/a5d5b638-fc38-47fd-954f-37caf362bfb7" />


---

### Program 7: Hidden Markov Model (HMM)
- Implemented HMM for phoneme sequence generation
- Defined phonemes: /s/, /p/, /ie:/, /tʃ/ with probabilities
- Created transition and emission probability matrices
- Generated random phoneme and observation sequences
- Showed probabilistic state transitions in speech

**Screenshot**
<img width="767" height="473" alt="image" src="https://github.com/user-attachments/assets/3673f85e-9f31-4d78-877a-ff214eb87baf" />


---

### Program 8: Viterbi Algorithm
- Implemented Viterbi algorithm for decoding hidden states
- Applied to recognize word "hello" phonemes: /h/, /e/, /l/, /o/
- Used HMM with transition and emission probabilities
- Found most likely phoneme sequence from observations
- Computed probability of decoded path (0.03704)
- Successfully decoded "hello" from acoustic features

**Screenshot**
<img width="786" height="156" alt="image" src="https://github.com/user-attachments/assets/9a467a31-f7cf-40d0-acb6-caff8d2182d7" />




