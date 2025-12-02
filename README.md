# Hybrid_MaxMSP_Synth_Studio — Hybrid Sample & Synthesis Workstation
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Max/MSP](https://img.shields.io/badge/Environment-Max%2FMSP-blue.svg)](https://cycling74.com/)
![Portfolio Project](https://img.shields.io/badge/Project-Type%3A%20Portfolio-0057b7.svg)
[![Hybrid Synthesis](https://img.shields.io/badge/Synthesis-Hybrid%20(Additive%20%2B%20Subtractive%20%2B%20FM)-purple.svg)](#)
![Sampler Engine](https://img.shields.io/badge/Sampler-Pitch%20Shift%20%7C%20Speed%20Control-teal.svg)
![FX Suite](https://img.shields.io/badge/FX-Reverb%20%7C%20Compression%20%7C%20Distortion-orange.svg)
![Custom UI](https://img.shields.io/badge/UI-Custom%20Synth%20Interface-grey.svg)
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

---

## Requirements

- Max 8 or later (Cycling '74)
- Audio interface or built-in system audio
- Recommended test settings:
  - DSP on (I/O Vector = 64, Signal Vector = 64)
  - Sample rate: 44.1 kHz
  - Buffer size ≤ 128 samples for smooth parameter modulation
- Works with:
  - MIDI keyboard (optional) for pitch and mod-wheel control
  - Mouse/trackpad input for UI sliders, knobs, and engine selectors
### Optional Enhancements
- Full-range studio monitors or headphones for accurate bass and FX response
- Sustain pedal for expressive sampler playback

---

## Real-World Applications
- **Sound design for games and interactive media**  
  Hybrid engine enables Foley-style textures, tonal synths, and evolving pads from a single workstation.
- **Film & TV scoring / trailer sound creation**  
  Combines synthetic layers with resampled audio to build signature stabs, pulses, risers, and atmospheres.
- **Electronic music production**  
  FM + subtractive + sample playback allows producers to create punchy bass, evolving leads, textured keys, and cinematic pads inside one patch.
- **Live performance rigs**  
  Macro-style FX section (reverb, compression, distortion) and mod wheel support makes the synth playable without external plugins.
- **SFX prototyping for game audio middleware (Wwise / FMOD)**  
  Rapidly designs procedural sounds that translate well into layered real-time systems.
- **Education / DSP learning environments**  
  Demonstrates synthesis concepts (additive | subtractive | FM | envelope shaping | portamento) within a visual signal-flow interface.
- **Sampling-based instruments and creative resampling**  
  Sampler + pitch/tempo control enables quick transformation of raw sounds into playable instruments.

This project highlights core competencies used in professional audio plug-in development, game audio systems, adaptive music engines, and digital instrument design.

---

© Henry Powell — Audio DSP Development
