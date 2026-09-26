# CSPC — Computer Science for Physics and Chemistry

My coursework repository for the course.
Each practical lives under `PW<n>/Lab <X>/`.

## PW1 — Lab A: Reproducible Foundations

### What I Did

1. Implemented and tested a stochastic radioactive decay simulation.
2. Added a test to check that negative decay rates raise a `ValueError`.
3. Added a test comparing the average simulation result with the analytical decay law.
4. Compared the performance of the loop-based implementation with the NumPy implementation.
5. Used `pytest` to verify that the implementation works correctly.

### What the Data Showed

The simulations show the expected decrease in the number of atoms over time.

### Comparison with the Analytical Law

The average of many stochastic simulations is close to the analytical decay law:

`N(t) = N0 * exp(-lambda * t)`

### Performance

The NumPy implementation is significantly faster than the Python loop implementation for the tested simulation.

### Conclusion

During this laboratory work, I learned how to test Python code with `pytest`, compare a stochastic simulation with an analytical model, and measure the performance of different implementations.

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
