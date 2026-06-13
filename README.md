# EMSC2010 – Week 5 Practical 1: Bootstrapping

This repository contains the template Jupyter notebook for **Week 5 Practical 1** of *EMSC2010: Data Science for Earth System Scientists* at the Australian National University.

The session introduces **bootstrapping** — a resampling technique for estimating the uncertainty of a statistic by repeatedly drawing random samples (with replacement) from an observed dataset.

---

## Notebook

### Notebook 1 – Bootstrapping the Alien Probe Dataset (`NB1`)

**Dataset:** A 25-point "Alien Probe" dataset of binary (0/1) observations, entered individually by each student.

This is a guided exercise notebook. Students begin by entering their own 25-value Alien Probe dataset as a `numpy` array, then use `np.random.choice` to generate **bootstrap samples** — resamples of the same size drawn with replacement from the original data. By repeatedly bootstrapping and recalculating a statistic of interest (e.g. the sample mean/proportion) across many resamples, students build up a distribution that can be used to estimate the uncertainty of that statistic, building directly on the random number generation concepts introduced in Week 5 Lectorial 1.

**Key concepts:** Bootstrapping, resampling with replacement, `np.random.choice`, estimating uncertainty from a single sample

**Libraries:** `numpy`

---

## Getting Started

This is a **template repository**. To begin working on the notebook:

1. Click **"Use this template"** at the top of this page to create a copy of the repository in your own GitHub account.
2. Open the notebook from your copy of the repository and click the **"Open in Colab"** badge at the top of the notebook to launch it in Google Colab.
3. Before submitting, replace the `uXXXXXXX` placeholder in the filename with your ANU student UID.

---

## Repository Structure

```
EMSC2010-W5-P1/
├── EMSC2010_W5_P1_NB1_uXXXXXXX.ipynb   # Bootstrapping the Alien Probe dataset
├── LICENSE
└── README.md
```

---

## Course Information

| | |
|---|---|
| **Course** | EMSC2010 – Data Science for Earth System Scientists |
| **Institution** | Australian National University (ANU) |
| **Week** | 5 |
| **Session** | Practical 1 |
| **Topic** | Bootstrapping |

---

## License

This repository is released under the [MIT License](LICENSE).
