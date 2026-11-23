# Dashboard Adaptation Note

## Audience

A public-health analyst preparing a short briefing on descriptive BMI patterns in the classroom NHANES equity dataset.

## Dashboard Question

Among adults age 20-80, how does mean BMI vary across NHANES cycles for one selected income group?

## Control And Visualization

- Control or interaction: drop down option
- Visualization affected: line graph shows mean BMI for High Income after selecting for that option
- What changes when the control changes: when the control changes, so does the visualisation and what BMI is shown

## Before And After

| Missing BMI []... ages are excluded| Missing BMI [...] ages are excluded. Please refer to exlcusion crietria for more explanation| This helps the audience understand why you exlcuded specific elements for clarity and transparency. |
|---|---|---|
|  |  |  |

## Test Result

After syncing the correct pathwya to my data set, I sorted for available income groups and then selected High Income. I then ran all cells again and clicked render. 

## Limitation

This starter is unweighted and descriptive. It does not account for NHANES survey design, does not estimate national prevalence, and should not be used to make causal claims about income and BMI.

## Privacy Check

- Use aggregate summaries, not row-level records.
- Avoid small-cell interpretations when `n` is low.
- State that outputs are descriptive and unweighted.
- Keep cached classroom data separate from any raw NHANES retrieval workflow.
- Do not upload row-level data to external AI tools.
