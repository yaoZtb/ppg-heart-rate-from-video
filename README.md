# Heart Rate from a Smartphone Video of a Finger

Estimating heart rate from a phone-camera video of a fingertip (photoplethysmography, PPG), using the FFT in Python.

## Contents
- `heart_rate_from_video.ipynb` – analysis notebook
  - Part 1: Extracting the PPG signal from the video
  - Part 2: Heart rate from the video signal: method validated on a synthetic 72 bpm test signal (FFT spectrum, heart-rate band search 42–210 bpm)
- `data/video_of_finger.MOV` – input video (~112 MB, stored with Git LFS)

## Getting the video
The video is tracked with [Git LFS](https://git-lfs.com). Install it before cloning:

```bash
git lfs install
git clone https://github.com/yaoZtb/ppg-heart-rate-from-video.git
```

## Requirements
Python 3, NumPy, Matplotlib, Jupyter.
