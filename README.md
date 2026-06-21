# QCurve — User Help & Guide

> Professional-grade audio enhancement and DSP tuning for Android
---
# Table of Contents

* 1. App Overview
* 2. Main Features Overview
* 3. Equalizer Controls
* 4. Preset System
* 5. Custom Presets
* 6. Dynamic EQ
* 7. Bass Boost
* 8. Balance Control
* 9. Spectrum Analyzer
* 10. Room Correction — Independent L/R Split
* 11. Device Profiles
* 12. Pro Audio Mastering
* 13. Premium Features
* 14. Appearance & Themes
* 15. Import & Export Presets
* 16. Audio Permissions Explained
* 17. Troubleshooting
* 18. Frequently Asked Questions
* 19. Tips for Best Audio Quality
* 20. Beginner Quick-Start Guide

---

# 1. App Overview

QCurve is a professional-grade audio enhancement and DSP tuning app designed for music enthusiasts, audiophiles, and power users.

Built around a high-fidelity 10-band equalization engine, QCurve combines precision audio shaping, intelligent volume-adaptive processing, room correction, device-aware profiles, and Pro Audio mastering tools into a clean modern interface.

Whether you are tuning headphones, correcting room acoustics, improving Bluetooth speakers, or creating studio-inspired sound profiles, QCurve delivers powerful real-time DSP processing while remaining intuitive for everyday listening.

---

# 2. Main Features Overview

* 10-Band Real-Time Equalizer: Free & Pro
* Built-In Presets: Free & Pro
* HyperCinema & Aurora Presets: Pro Only
* Dynamic EQ: Free & Pro
* Bass Boost: Free & Pro
* Balance Control: Free & Pro
* Spectrum Analyzer: Free & Pro
* Premium Visualizer Styles: Pro Only
* Custom Presets: Free & Pro
* Device Profiles: 2 Devices (Free) / Unlimited (Pro)
* Room Correction (L/R Split): Pro Only
* Pro Audio Mastering: Pro Only
* Expert Multi-Band Compressor Editor: Pro Only
* Import / Export .qcurve Presets: Free & Pro
* Multiple Themes: Free & Pro

---

# 3. Equalizer Controls

## Overview
QCurve uses a precision 10-band equalizer covering the full audible spectrum. Each band can be boosted or reduced independently in real time.

## Frequency Bands
* Band 1: 40 Hz
* Band 2: 60 Hz
* Band 3: 120 Hz
* Band 4: 230 Hz
* Band 5: 450 Hz
* Band 6: 910 Hz
* Band 7: 1.8 kHz
* Band 8: 3.6 kHz
* Band 9: 7 kHz
* Band 10: 14 kHz

## Using the Sliders
* Drag upward to boost frequencies.
* Drag downward to reduce frequencies.
* Floating tooltips display exact dB values while adjusting.
* Sliders automatically snap to 0 dB for quick neutral restoration.

## Preset State Tracking
When you manually modify a preset, the active preset label changes to **Custom**. If all sliders are returned exactly to the original preset positions, the preset name is automatically restored.

## Protection & Headroom
QCurve automatically manages headroom and limiting internally to reduce clipping and distortion during heavy boosts.

---

# 4. Preset System

QCurve includes carefully tuned built-in presets optimized for different listening styles and genres.

## Standard Presets
* Flat, Bass Boost, Vocal, Treble, V Shape, Pop, Rock, Acoustic, Hip Hop, Jazz, Precision, Titan Bass

## Premium Presets
### HyperCinema ✦
Wide cinematic staging with powerful controlled dynamics.

### Aurora ✦
Smooth airy extension with balanced low-end warmth and open highs.

Premium presets are marked with a premium indicator and require QCurve Pro.

## Switching Presets
Tap any preset chip to instantly load the preset. EQ sliders animate smoothly into position.

---

# 5. Custom Presets

## Saving Presets
After tuning your sound:
1. Tap **Save**
2. Enter a preset name
3. Confirm

QCurve stores EQ band levels, Left/Right Room Correction data, Mastering settings, Expert MBC parameters, and Macro preset states.

## Managing Presets
Saved presets can be applied, shared, exported, or deleted.

## Smart Device Assignment
If Device Profiles are enabled, QCurve can automatically associate newly saved presets with connected devices.

---

# 6. Dynamic EQ

## What It Does
Dynamic EQ intelligently compensates for how human hearing changes at lower listening volumes. At low volume, bass and highs become less audible. Dynamic EQ automatically restores balance using equal-loudness compensation based on ISO 226 principles.

## How to Use
1. Enable Dynamic EQ
2. Adjust the Strength slider (Recommended starting range: 60–80%)

At higher playback volumes, Dynamic EQ gradually reduces its effect automatically.

## Intelligent Interaction
Dynamic EQ is aware of your manual EQ boosts and reduces excessive stacking to maintain cleaner output.

---

# 7. Bass Boost

## Overview
Bass Boost applies a dedicated low-frequency enhancement focused primarily on lower frequencies.

## Smart Gain Management
If bass frequencies are already heavily boosted manually, QCurve automatically scales Bass Boost intensity to reduce distortion and clipping.

---

# 8. Balance Control

The Balance control adjusts the relative loudness between the left and right channels. Center position restores equal balance. The transition uses smooth gain curves for natural stereo panning.

---

# 9. Spectrum Analyzer

## Overview
The Spectrum Analyzer displays a real-time visualization of your audio playback using real-time FFT rendering.

## Controls
* Enable using the Spectrum toggle
* Tap analyzer to cycle styles
* Use the Palette button to open the visualizer style selector
* When disabled, the analyzer collapses to conserve resources.

---

# 10. Room Correction — Independent L/R Split

> QCurve Pro Feature

## Overview
Room Correction allows completely independent EQ curves for the Left and Right channels. Useful for uneven room acoustics, headphone imbalance, or off-center listening positions.

## How It Works
1. Enable Room Correction
2. Select Left or Right channel
3. Adjust the EQ separately for each side (sliders will change color based on the active channel).

---

# 11. Device Profiles

## Overview
Device Profiles automatically load presets based on connected audio hardware (Bluetooth headphones, speakers, wired sets, USB audio, etc.).

## Setup
1. Open Device Profiles
2. Select a connected device
3. Assign a preset
4. QCurve automatically applies the assigned preset whenever the device reconnects.

Free users can assign up to 2 devices. Pro users have unlimited devices.

---

# 12. Pro Audio Mastering

> QCurve Pro Feature

## Overview
Pro Audio Mastering enables a professional 10-band Multi-Band Compressor (MBC) engine operating across the audio spectrum.

## Macro Presets
* **Tight Punch:** Fast low-end compression for punchier bass.
* **Vocal Focus:** Enhances vocal clarity and midrange presence.
* **Cinematic Air:** Smooth airy top-end enhancement with relaxed dynamics.

## Expert Mode
Enable Expert Mode and long-press any EQ band to manually edit Threshold, Ratio, Attack, Release, and Knee Width independently per frequency band.

---

# 13. Premium Features

QCurve Pro unlocks the HyperCinema and Aurora presets, Room Correction, Pro Audio Mastering, Expert Mode, Premium visualizer styles, and Unlimited Device Profiles.

The core EQ, Dynamic EQ, Bass Boost, standard presets, and custom presets remain fully usable in the free version.

---

# 14. Appearance & Themes

* **Clean Light:** Bright minimal interface
* **Studio Dark:** Professional studio-style dark mode
* **Graphite Blue:** Modern DSP-inspired dark blue aesthetic
* **Warm Amber:** Vintage-inspired warm studio tone

---

# 15. Import & Export Presets

QCurve uses the `.qcurve` preset format to export custom configurations via email, messaging apps, or cloud storage. Import presets by opening a `.qcurve` file or using the import option inside QCurve.

---

# 16. Audio Permissions Explained

Android requires microphone permission for real-time audio visualization through the Spectrum Analyzer. QCurve DOES NOT record, store, or upload audio. Audio processing remains fully local on-device.

---

# 17. Troubleshooting

* **EQ Has No Effect:** Ensure the main EQ toggle is ON, restart playback, or toggle the EQ off/on.
* **Spectrum Analyzer Not Working:** Verify microphone permission is granted and re-enable the Spectrum toggle.
* **Imported Preset Failed:** Try importing again from the original exported file.
* **Preset Changed to “Custom”:** This happens when the active preset is manually modified.

---

# 18. Frequently Asked Questions

* **Does QCurve Work System-Wide?** Yes, it uses Android's DynamicsProcessing engine and works with most system audio playback.
* **Does QCurve Drain Battery?** Normal DSP processing has minimal impact. The Spectrum Analyzer uses additional resources while active.
* **Will I Lose My Presets After Upgrading to Pro?** No. Existing presets and settings remain intact.

---

# 19. Tips for Best Audio Quality

## For Audiophiles
* Start from Flat or Precision
* Use moderate boosts and prefer cuts over excessive boosts
* Keep Dynamic EQ lower at high listening volumes

## For Casual Listening
* Start with built-in presets
* Use Dynamic EQ around 70%
* Use Bass Boost moderately

---

# 20. Beginner Quick-Start Guide

1. **Enable the EQ:** Turn ON the main EQ switch.
2. **Select a Preset:** Choose a preset matching your listening style.
3. **Enable Dynamic EQ:** Set Dynamic EQ around 60–70% for fuller low-volume listening.
4. **Fine Tune:** Adjust a few bands gently if needed.
5. **Save Your Setup:** Tap Save and store your custom sound profile.
6. **Assign Device Profiles:** Assign presets to your headphones or speakers for automatic switching.

---

> QCurve — Built for audio enthusiasts.
