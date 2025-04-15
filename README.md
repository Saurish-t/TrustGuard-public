# TrustGuard-public
---

# TrustGuard
For project privacy keeping the github https://github.com/Saurish-t/Lie-detection private <br>
**TrustGuard** is an AI-powered deception detection platform that uses a multimodal fusion of audio and visual data to analyze whether a person is lying. Built to enhance digital communication integrity, TrustGuard can be used in interviews, virtual meetings, or online safety applications where trust is critical.

## Problem

In an increasingly virtual world, it has become harder to determine the authenticity of what people say. Whether it’s during a job interview, a virtual negotiation, or a safety-critical conversation, the inability to detect deception in real-time can lead to misinformation, manipulation, and poor decision-making.

Traditional lie detectors are invasive, inaccurate, and unsuitable for real-world or remote use. There's a need for a non-invasive, real-time, and context-aware lie detection system.

## Solution

**TrustGuard** uses a fusion of **audio** and **video** signals to detect subtle indicators of deception using machine learning models trained on labeled datasets of truthful and deceptive speech.

### How It Works

- **Audio Analysis**
  - Extracts vocal features such as pitch variation, micro-pauses, and hesitations using pretrained audio models
  - Detects voice stress and inconsistency using spectral features

- **Visual Analysis**
  - Uses facial emotion recognition and micro-expression analysis (e.g., blinking, lip movements, facial tension)
  - Detects nonverbal cues often associated with deception

- **Fusion Model**
  - Combines predictions from both audio and video branches using a neural fusion model
  - Final classification score indicates the likelihood of truthfulness in real-time

## Features

- Real-time lie detection during video calls or recordings
- Multimodal input processing (audio + facial video)
- Scoring dashboard showing deception probability
- Visual heatmaps of facial tension and vocal stress regions
- Modular ML pipeline for future enhancements or deployment

## Technical Stack

- **Audio**: Python with LibROSA, OpenSMILE for feature extraction
- **Video**: OpenCV and deep learning facial expression analysis
- **Modeling**: Custom fusion neural network trained on open-source deception datasets
- **Interface**: Streamlit prototype for demo; future support planned for browser-based and mobile integration

## Inspiration

TrustGuard was inspired by the growing demand for trust verification in remote settings. From online interviews to digital safety investigations, the need for an accurate, non-invasive lie detection tool is greater than ever. Our team wanted to bridge this gap using cutting-edge AI.

## Achievements

- **2nd Best Overall** at **AcademiesHacks**
- Recognized for innovative multimodal approach and real-world applicability

## Future Work

- Expand dataset to improve generalization across accents and expressions
- Incorporate contextual language models for semantic-level lie detection
- Launch as a browser plugin or Zoom-compatible extension

---
