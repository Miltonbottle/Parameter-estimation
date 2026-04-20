# 📘 Parameter Estimation Assignment (Predictive Analysis)

This repository contains solutions and derivations for a **Parameter Estimation** assignment, focusing on statistical inference using **Maximum Likelihood Estimation (MLE)** and estimator properties.

The work is based on handwritten derivations provided in the uploaded document.

---

## 📂 Contents

- **Q1:** MLE for Normal Distribution Parameters  
- **Q2:** Estimation in Binomial Distribution  
- Supporting concepts:
  - Likelihood and log-likelihood
  - Parameter estimation
  - Unbiased estimators
  - Mean Squared Error (MSE)

---

## 🧮 Problem Overview

### 🔹 Question 1: Normal Distribution Parameter Estimation

Assume observations are **i.i.d.** from a normal distribution:

- Mean: \( \theta_1 \)  
- Variance: \( \theta_2 \)

#### Steps:

1. Construct the **joint likelihood function**  
2. Take the **log-likelihood**  
3. Differentiate with respect to parameters  
4. Solve for estimates  

#### Results:

- **MLE of Mean:**
  \[
  \hat{\theta}_1 = \bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i
  \]

- **MLE of Variance:**
  \[
  \hat{\theta}_2 = \frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^2
  \]

---

### 🔹 Question 2: Binomial Distribution Estimation

Given:
- \( X \sim \text{Binomial}(m, \theta) \)

#### Known:

- \( E[X] = m\theta \)  
- \( \text{Var}(X) = m\theta(1 - \theta) \)

#### Estimator:

\[
\hat{\theta} = \frac{\bar{X}}{m}
\]

---

## 📊 Statistical Properties

### ✔️ Unbiasedness

\[
E[\hat{\theta}] = \theta
\]

### ✔️ Mean Squared Error (MSE)

Since the estimator is unbiased:

\[
\text{MSE}(\hat{\theta}) = \text{Var}(\hat{\theta})
\]

\[
\text{MSE}(\hat{\theta}) = \frac{\theta(1 - \theta)}{mn}
\]

---

## 🧠 Key Concepts

- Maximum Likelihood Estimation (MLE)
- Log-likelihood optimization
- Sample mean and variance
- Bias and unbiasedness
- Mean Squared Error (MSE)
- Normal and Binomial distributions

---

## 📝 Notes

- Derivations follow a step-by-step analytical approach.
- Includes differentiation of log-likelihood and solving normal equations.
- Results align with standard statistical theory.

---

## 🚀 Usage

- Study MLE derivations for exams or coursework  
- Use formulas as a reference  
- Extend methods to other distributions  

---

## 📄 Source

Based on handwritten assignment:
**Parameter Estimation – Predictive Analysis**
