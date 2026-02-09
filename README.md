# Audio Signal Processing – Medien Project

University project for audio signal processing. Contains code for assignments (Blatt 3–6): quantization, sampling, filtering, and convolution.

## Structure

- **notebooks/** – Jupyter notebooks (Blatt 3–6)
- **data/** – Input audio files and reference data
- **results/** – Generated figures, audio outputs, and saved coefficients
- **report/** – LaTeX report (or placeholder)
- **scripts/** – Optional Python scripts

## Requirements

- Python 3 (3.10+ recommended)
- Dependencies: `numpy`, `soundfile`, `matplotlib`, `scipy`, `jupyter`

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run

1. Start Jupyter: `jupyter notebook` or `jupyter lab`
2. Open notebooks from the **notebooks/** folder.
3. Run in order: Blatt 3 → Blatt 4 → Blatt 5 → Blatt 6 (some later notebooks use outputs from earlier ones).
4. Input data is in **data/**; generated figures and audio are written to **results/figures/** and **results/audio/**.

## Report

The written report is in **report/** (or submitted separately). Figures used in the report are in **results/figures/**.
