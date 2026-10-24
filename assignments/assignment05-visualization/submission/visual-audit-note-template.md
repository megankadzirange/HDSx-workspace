# Visual Audit Note

## Plot Question

Write the descriptive question the plot answers.

The descriptive question the plot answers is: How is BMI related to income level, over time?

## Issues Checked

<!-- AI-EDIT(2026-06-11): SS-035 — worked example row added — needs review -->
The first row is a worked example of the expected shape — replace it with your own issue.

| Issue | Category | Why it matters | Correction |
|---|---|---|---|
| *Example: y-axis starts at 22 instead of 0* | *Correctness* | *Exaggerates the BMI gap between groups, suggesting a larger difference than the data show* | *Start the y-axis at 0 (or show the full data range) and state the axis choice in the caption* |
|Title suggests causation between low income and obesity  | Correctness |it falsely presents the data as causal instead of cor-relational  | emphasise that income is correlated with rising obesity in American adults |
|x-axis is divided into wo categories, and also each actegory does not contain the same number of years | Correctness |this makes the timeline misleading and prevents readers from accurately interpreting changes in BMI over time  | Use a continuous x-axis representing years with proportional spacing, and plot additional NHANES cycles to more accurately illustrate BMI trends over time. |
|The graph uses dashed lines to connect only two data points per income group | Design | this misleadingly suggests a continuous and steady increase in BMI over time | Replace the dashed lines with individual data points (a scatter plot) to avoid implying trends that cannot be confirmed without additional observations |

## Final Caption

This figure shows mean body mass index (BMI) by income group across selected NHANES cycles using the prepared NHANES Health Equity classroom dataset. The summary is descriptive and unweighted. Records with missing BMI or income group values were excluded. The plot supports comparison of BMI patterns across income groups over time, but does not establish causal relationships or provide population-level estimates..

## AI-Use Check

AI helped develop the corrected graph, including changes to a scatter plot and suggestions for a beter title. Claims were checked by comparing the new code to the flawed code to ensure the desired chnages were indeed implemented

