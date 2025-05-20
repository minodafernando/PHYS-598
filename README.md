# 📡 Honors Thesis: Ionospheric Absorption Analysis Using Ionosonde and Riometer Data

This repository contains code and visualizations developed for my honors thesis in Physics at the University of Calgary. The thesis investigates the correlation between ionosonde signal dropouts and high-frequency wave absorption, using data from Gakona, Alaska (ionosonde) and Dawson, Yukon (riometer).

---

## 🧠 Background

**Ionosphere**: A charged region of the Earth's upper atmosphere (50–1000 km altitude), composed of free electrons and ions. It consists of D, E, and F layers — this project focuses on the **D and E layers**.

**Ionosonde**: A radar system that sends vertical radio pulses to measure the ionosphere’s electron density by analyzing signal reflections and frequency shifts.

**Riometer**: An instrument that detects cosmic radio noise absorption, which varies with electron density in the ionosphere.

**Appleton–Hartree Equation**: Describes how high-frequency (HF) wave absorption is influenced by collisions between ionized and neutral particles in the ionosphere.

---

## 🎯 Goal

To determine whether missing values in the Gakona ionosonde data are linked to periods of high absorption detected by the Dawson riometer. This was tested under the hypothesis that **HF wave absorption during high-density events disrupts ionosonde signal reflection**, causing data gaps.

---

## 🔬 Method Overview

- Selected the year **2012** after plotting ionosonde trends from 2012–2022 and identifying it as the most consistent dataset.
- Chose individual days with **absorption > 3 dB** to analyze severe events (since low-absorption events are less detectable).
- Conducted a **1-day case study**, followed by **12-day expanded analysis** on the highest absorption events.
- Used **matplotlib** to compare absorption peaks against ionosonde data dropouts.
- Patterns were consistent with predictions from the **Appleton–Hartree equation**.

---

## 📚 References

[1] McElroy, M. B. (2023), *Ionosphere and Magnetosphere*, Encyclopædia Britannica  
[2] PITHIA-NRF, *Ionosonde Instrument Overview*  
[3] Fiori, R. A. D., & Danskin, D. W. (2016). *AGU Publications* — [Link](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2016SW001461)

---

## ✍️ Author

Minoda Fernando  
BSc in Physics – University of Calgary 
