# MATLAB Audio Signal Processing & Analysis App

## Overview
This project is an interactive Graphical User Interface (GUI) developed in **MATLAB App Designer**. It serves as an educational and analytical tool for **Digital Signal Processing (DSP)** concepts. 

The application allows users to generate, record, analyze, and process audio signals in real-time, providing a dual-view interface to compare original signals against processed versions (A/B testing) both visually and aurally.

## Key Features

### 1. Signal Acquisition & Generation
* **Audio Import:** Load standard audio files (`.wav`, `.mp3`, etc.).
* **Signal Generator:** Create synthetic waveforms including Sine, Square (adjustable duty cycle), Triangular (adjustable symmetry), Sawtooth, and Trapezoidal.
* **Live Recording:** Capture audio directly from the microphone.

### 2. Analysis & Visualization
The app provides three synchronized visualization domains for both input and output signals:
* **Time Domain:** Waveform amplitude over time.
* **Frequency Domain (FFT):** Magnitude spectrum analysis.
* **Spectrogram:** Time-frequency analysis (STFT) with adjustable windowing, optimized for speech processing.

### 3. Signal Processing Modules
* **Aliasing Demonstration:** Custom downsampling module to visualize the Nyquist-Shannon sampling theorem violation, including spectral folding effects.
* **Modulation:** Implementation of Amplitude Modulation (AM) and Frequency Modulation (FM) with demodulation capabilities.
* **Filtering:** Low-Pass Filter (Butterworth) design for signal recovery and noise reduction.
* **Noise Injection:** Additive Gaussian White Noise (AWGN) with adjustable power.
* **Time Operations:** Time compression/expansion and time reversal.
* **Signal Mixing:** Capability to combine multiple signals into a single output.

### 4. Measurements
* **Power Calculation:** RMS power calculation in dBFS.
* **SPL Estimation:** Sound Pressure Level estimation based on calibration points.

## Technical Highlights
* **Dual-Player Architecture:** Independent audio players for the *Original* (Top) and *Processed* (Bottom) signals, allowing for immediate auditory comparison.
* **Memory Management:** Efficient handling of temporary processed data to optimize performance during iterative testing.
* **Visual Synchronization:** Playback markers (red cursor) are synchronized across time plots for precise analysis.

## Requirements
* MATLAB R2020b or later.
* Signal Processing Toolbox.

## How to Run
1.  Clone this repository.
2.  Open MATLAB.
3.  Navigate to the project folder.
4.  Open `app1.mlapp` (or the project file name) in App Designer.
5.  Click **Run**.

**Author:** Lucía Gutiérrez Bartolomé
**Contact:** www.linkedin.com/in/lucia-gutierrez-bartolome-teleco
