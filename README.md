# Hybrid_MaxMSP_Synth_Studio — Hybrid Sample & Synthesis Workstation
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Max/MSP](https://img.shields.io/badge/Max%2FMSP-Visual%20DSP%20Environment-blue.svg)
![Hybrid Synthesis](https://img.shields.io/badge/Synthesis-Hybrid%20(Additive%20%2B%20Subtractive%20%2B%20FM)-purple.svg)
![Built-in FX](https://img.shields.io/badge/FX-Reverb%20%7C%20Compression%20%7C%20Distortion-orange.svg)
![Sampler Engine](https://img.shields.io/badge/Sampler-Pitch%20Shift%20%2F%20Speed%20Control-teal.svg)
![UI](https://img.shields.io/badge/UI-Custom%20Synth%20Interface-grey.svg)
![Grad Program](https://img.shields.io/badge/Grad_Program-Audio_Technology_(M.A.)-6a1b9a.svg)
![University](https://img.shields.io/badge/American_University-Washington,_DC-002855.svg)

Hybrid_MaxMSP_Synth_Studio is a Max/MSP patch that blends subtractive synthesis, modulation synthesis, canonical waveforms, and sample-based sound manipulation into a single unified workstation.
The design focuses on musical flexibility, intuitive UI control, smooth transitions between notes, and real-time sound-design capabilities.

---

## Features

- **Canonical Waveforms**
    Sine, Sawtooth, Square, Triangle

- **Additive & Subtractive Engines**
    Flexible harmonic control multiple filter types  

- **Modulation Synthesis**
    Ring Modulation, Amplitude Modulation, & Frequency Modulation   

- **ADSR Envelope Generator**
    Adjustable Attack, Decay, Sustain, Release

- **Portamento Glide**
    10–1000 ms smooth sliding between notes

- **Effects Section**
    Reverb, Compression, & Distortion   

- **Sample Rack**
    Polyphonic sampler with Pitch Shifting & Speed Control   

- **MIDI Input & Mod Wheel Support**
    Full keyboard range modulation control 

- **Audio Spectrum Analyzer**
    Real-time visual feed of the output signal

  ---

  ## File Contents

| File | Description |
|------|-------------|
| `Hybrid_MaxMSP_Synth_Studio.maxpat` | Main synthesizer workstation patch |
| `UI_Screenshot.png` | Interface screenshot of the synth |

---

## How to Use

1. Open `Hybrid_MaxMSP_Synth_Studio.maxpat` in **Max 8 or later**
2. Select an oscillator waveform using the **Canonical Waveforms** panel
3. Choose synthesis mode (Additive or Subtractive)
4. Adjust **ADSR**, **Portamento**, and **Modulation** parameters as desired
5. Load a sample into the **Sample Rack** to activate sampler playback
6. Trigger notes via **MIDI keyboard** or on-screen UI
7. Shape the tone using **EQ and effects (Reverb / Compression / Distortion)**
8. Monitor the output via the **Audio Spectrum Analyzer**

---

## Development Environment

- Max/MSP 8+
- macOS
- MIDI Controller (optional but supported)

---

## Engineering Relevance

Hybrid_MaxMSP_Synth_Studio demonstrates applied DSP and music-technology design concepts including:

- Real-time waveform, modulation, and sample-based sound generation
- Dynamic UI-controlled synthesis parameters mapped to DSP processes
- Sample-rate-synchronous envelope and glide smoothing to prevent clicks
- Signal routing based on modular synthesis architecture
- Effects processing chain similar to commercial audio workstations
- MIDI input parsing, velocity mapping, and modulation wheel integration

This project highlights core competencies used in professional audio plug-in development, game audio systems, adaptive music engines, and digital instrument design.

---

© Henry Powell — Audio DSP Development
