# CSPC — Computer Science for Physics and Chemistry

My coursework repository for the course.
Each practical lives under `PW<n>/Lab <X>/`.

## Setup

Create and activate the environment for a given lab:

```bash
conda env create -f "PW<n>/Lab <X>/environment.yml"
conda activate cspc
```

Run the tests for a lab from inside its folder:

```bash
cd "PW<n>/Lab <X>"
pytest -v
```

---

## PW1 — Lab A: Reproducible Foundations

**What I built:**
- <one or two lines: the CSPC repo, the environment, the decay simulation, the tests>

**Speed comparison (loop vs NumPy):**

| version | time (s) |
|---------|----------|
| pure-Python loop | ... |
| NumPy (vectorised) | ... |

- Speed-up: **... × faster**

**Tests:** all passing? (yes / no)

**Conclusion:**
- <2–3 sentences: what worked, what you learned, any problems you hit and how you solved them>

---

<!-- Future sessions: add a new "## PW<n> — Lab <X>" section below. -->
## PW1 — Lab B

### What I Did

1. Checked and installed the required tools and packages for Lab B, such as `matplotlib` and `snakemake`.
2. Loaded and worked with the observed decay data from the provided file.
3. Calculated the analytical decay values using the given decay law.
4. Created a plot comparing the observed data with the analytical decay curve using `matplotlib` and saved it as `figure.png`.
5. Used Snakemake to automate the plotting process and learned about the advantages of workflow automation.

### What the Data Showed

The observed data show a decrease in the number of atoms over time, which is consistent with the expected behaviour of radioactive decay.

### Comparison with the Analytical Law

The observed data approximately follow the analytical decay curve, with some differences due to the stochastic nature of the observations.

### Snakemake Pipeline

The Snakemake pipeline uses `decay_observed.csv` as input and runs `plot.py` to generate `figure.png`.

### Conclusion

During this laboratory work, I studied the basic features of `matplotlib` and the advantages of Snakemake. I also learned how to visualize data and how Snakemake can create a consistent and reproducible pipeline for automating computational tasks.
