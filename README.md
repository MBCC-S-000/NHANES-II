# NHANES-II

Overview

This project examines the association between total alcohol consumption and all-cause mortality using data from the Second National Health and Nutrition Examination Survey (NHANES II) Mortality Follow-Up Study. The analysis applies survival analysis methods to evaluate whether different levels of alcohol intake are associated with mortality risk, and whether these associations differ by sex.

The study is designed as a methodological and applied epidemiology exercise, emphasizing model choice, assumption checking, confounding control, and sensitivity analyses.

Study Design

Population: U.S. adults aged 29–74 years at baseline

Sample size: 9,215 participants

Follow-up: Median 14 years (vital status through 1992)

Outcome: All-cause mortality

Exposure: Total self-reported alcohol consumption (drinks/week), categorized as:

0 drinks/week

1–7 drinks/week (reference)

8–14 drinks/week

14 drinks/week

Statistical Methods

The primary analytical approach is Cox proportional hazards regression, chosen for its flexibility in handling time-to-event data and censoring.

Key methodological features include:

Stepwise adjustment models (age; age + sex + race; fully adjusted models)

Formal testing of the proportional hazards assumption

Interpretation of hazard ratios as average effects over follow-up when PH assumptions are violated

Assessment of effect modification by sex using both stratified models and interaction terms

Poisson regression as a sensitivity analysis with person-time offsets

Multiple sensitivity analyses addressing:

Reverse causation

Alternative exposure categorizations (quartiles)

Additional confounding by lipid biomarkers

All analyses were conducted using SAS 9.4.

Key Results (Summary)

Overall, total alcohol intake was not strongly associated with all-cause mortality after multivariable adjustment.

Associations differed by sex:

Among women, high alcohol intake (>14 drinks/week) showed a stronger association with increased mortality risk.

Among men, both abstinence and high intake were modestly associated with higher mortality compared with moderate intake.

Sensitivity analyses yielded consistent results, supporting the robustness of the findings while highlighting potential reverse causation and exposure misclassification.

Limitations

This project explicitly addresses several important epidemiologic limitations:

Unclear timing of baseline variable assessment

Potential reverse causation

Exposure misclassification due to lack of drinking pattern data

Residual confounding

Limited power for cause-specific mortality analyses

These limitations are treated as part of the analytical discussion rather than shortcomings to be ignored.
