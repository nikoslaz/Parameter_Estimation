# Parameter Estimation

## Overview
Implementation of parameter estimation techniques including:
- Maximum Likelihood Estimation (MLE) for Poisson distribution
- Birthday problem probability calculations
- Bayesian inference for teacher's birthday estimation

## Assignment Tasks

### Question A: Poisson MLE
1. Derive and implement Poisson MLE:
   - Likelihood function derivation
   - Log-likelihood simplification
   - λ estimation from samples
2. Experimental validation with `numpy.random.poisson`

### Question B: Birthday Problems
**Part 1: Classic Birthday Problem**
1. Probability calculations for:
   - Different birthdays
   - All combinations in class of 23
2. Implement probability function for m children
3. Determine minimum class size for certain shared birthday

**Part 2: Bayesian Birthday Estimation**
1. Implement Bayesian probability function for:
   - Single left guess probability
   - Sequential left guesses
   - Combined evidence evaluation
2. Plot posterior probability distribution
3. Determine most probable birthday date

## Technical Requirements
- Implemented in Google Colab (Python)
- Allowed libraries: NumPy, Matplotlib
- No AI assistance permitted
- Single `.ipynb` file submission with:
  - Clear code blocks per question
  - Brief explanatory text
  - Visualizations where required

## Deliverable
- Complete implementation in one Colab notebook
- Mathematical derivations in comments/Latex
- Experimental results and analysis
- Probability distribution plots
