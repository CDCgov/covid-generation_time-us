# Running the code

- **Estimate generation time across all data stratifications:**  
   Run `main.R`. This will process all available data stratifications in parallel and output results.

- **Estimate for a specific data stratification:**  
   Run `main_scenario.R`. This script allows you to specify a single data stratification and performs parameter setup, Bayesian MCMC estimation, and plotting of posterior distributions.

- **Calculate 95% credible intervals for the serial interval:**  
   Run `main_serial_ci_mech.R`.

## Directories

| Directory | Contents |
|-----------|----------|
| `Data` | UK household demo data (Hart et al. 2022), data formatting scripts, and functions to calculate infection and symptom time boundaries for imputation |
| `Parameters` | Incubation period distributions and results folder naming conventions |
| `Functions` | Model estimation functions, prior assumptions, and MCMC likelihood calculations |
| `Scripts` | Bayesian MCMC framework and post-processing scripts for generation time calculation |
| `Plotting_code` | Figure generation scripts |
| `Results` | Posterior distributions from 1,000,000 iterations (US household data) |
