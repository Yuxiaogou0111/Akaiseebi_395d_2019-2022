---

## 1. Overview

This folder contains post-processed outputs from the particle tracking simulation for 
planktonic Panulirus brunneiflagellum.

The results are organized into:

- Animated trajectory visualization (GIF)
- Daily frame images (PNG sequence)
- Return rate statistics (CSV)

These files are intended for visualization, quantitative evaluation, and supplementary material.

---

## 2. GIF Animation
Description:
- Red: Mukojima; Green: Chichijima; Blue: Hahajima
- Displays daily particle positions
- Shows spatial dispersion over time
- Useful for qualitative trajectory interpretation

The animation represents passive advection under modeled current fields.

---

## 3. Frame Images (PNG Sequence)

Each frame corresponds to one simulation day.

Contents of each frame:
- Geographic map projection
- Particle locations
- Simulation date or day index

These frames can be:
- Used for high-resolution movie production
- Combined into alternative animation formats
- Used as individual supplementary figures

---

## 4. Return Rate CSV

Structure:

| Column Name | Description |
|-------------|-------------|
| day | Simulation day index |
| date | Calendar date |
| n_total | Total number of particles |
| n_returned | Number of particles inside release region |
| return_rate | n_returned / n_total |

Interpretation:

- return_rate = 1 → All particles remain/return
- return_rate = 0 → Complete export
- Intermediate values indicate partial retention

Return rate reflects physical transport only.

---

## 5. Notes

- Missing frames indicate incomplete simulation output.
- If GIF appears truncated, regenerate from full frame sequence.
- Return rate values depend on the definition of release region.

---

End of README.
"""
