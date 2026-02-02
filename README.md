This project presents a full end-to-end statistical analysis of a large-scale sunscreen usage and attitudes survey conducted in collaboration with a Stony Brook University School of Medicine research team. The goal of the analysis was to identify behavioral, knowledge-based, and structural drivers of sunscreen use and prevention behaviors, with an emphasis on producing clinically interpretable results suitable for publication.
The analysis is documented in the accompanying PDF report, which contains all data cleaning and transformation which is needed before modeling and diagnostics
Dataset Description

Sample size: 1,008 respondents

Variables: 67 original survey variables

Data type: Structured survey data collected via REDCap

Content areas include:

Demographics and school affiliation

Sunscreen usage frequency and seasonality

Application locations and body coverage

Perceived incentives and barriers

Knowledge and prevention beliefs

Awareness of free sunscreen dispensers

For privacy and IRB-related reasons, the raw dataset and original survey instrument are not publicly shared.

Methods

The analysis was conducted entirely in R using reproducible workflows. Key methodological steps included:

Data cleaning and reduction

Removed administrative and free-text fields

Collapsed sparse categorical levels

Validated multi-select responses and identified invalid combinations

Feature engineering

Converted multi-column seasonal responses into single ordinal application-frequency variables

Recoded binary, ordinal, and multinomial responses for modeling consistency

Exploratory data analysis

Distributional analysis and contingency tables

Visualization of usage patterns and incentives

Statistical modeling

Ordinal logistic regression for ordered outcomes

Multinomial logistic regression for categorical behaviors

Multiple-testing control using Benjamini–Hochberg–adjusted p-values

Diagnostics and interpretability

Association measures (e.g., Cramér’s V)

Multicollinearity checks (VIF)

