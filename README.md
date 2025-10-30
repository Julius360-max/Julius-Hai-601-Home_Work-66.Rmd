# STAT 601 – Week 6 Project

This repository contains my R Markdown (`.Rmd`) and rendered PDF file for Week 6 of STAT 601: Modern Applied Statistics I.  
The assignment focuses on hypothesis testing, confidence interval construction, and statistical interpretation using real-world decision rules.

##  Contents
- **Julius Hai 601 Home_Work 66.Rmd** – R Markdown source file containing code, computations, and interpretations.  
- **Julius Hai Home_Work 6.pdf** – Rendered PDF output with complete solutions and formatted results.

##  Topics Covered

### 1.  One- and Two-Sample Hypothesis Testing
Hypothesis testing is a statistical approach used to determine whether there is enough evidence from sample data to support or reject a claim about a population parameter.  

- **One-sample test:** Compares a single sample mean to a known or hypothesized population mean.  
- **Two-sample test:** Compares means between two independent groups to determine if a significant difference exists.  

These tests are essential for evaluating whether observed differences reflect actual effects or are due to random variation.

---

###  Welch–Satterthwaite t-test
The **Welch–Satterthwaite t-test** is a modified version of the two-sample t-test that adjusts for **unequal variances** and **unequal sample sizes** between groups.  
Unlike the traditional Student’s t-test, it does not assume equal population variance, making it more robust and realistic in applied data settings.  

This test calculates an adjusted degree of freedom using the Welch–Satterthwaite formula, providing a more reliable p-value when testing for differences between two sample means.

---

###  Confidence Interval Construction
A **confidence interval (CI)** gives a range of plausible values for a population mean (or mean difference) based on sample data.  
A 95% CI means that, if repeated many times, 95% of those intervals would contain the true mean.  

In this assignment, the CI complements hypothesis testing by showing the magnitude and direction of mean differences — allowing not only a yes/no decision but also practical insight into effect size and uncertainty.

---

###  Interpretation of Test Statistics and Decision Rules
A **test statistic** (such as the t-value) quantifies how far the observed data deviate from what is expected under the null hypothesis.  

The **decision rule** guides statistical conclusions:  
- If *p-value < α (0.05)* → Reject the null hypothesis (significant difference).  
- If *p-value ≥ α* → Fail to reject the null hypothesis (no significant evidence of difference).  

Interpretation extends beyond numbers — explaining what statistical results mean in real-world terms, such as identifying whether one process, treatment, or group truly performs better.

---

##  Author
**Julius Hai**  
Graduate Student – South Dakota State University

