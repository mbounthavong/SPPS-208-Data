
URL: https://datadryad.org/stash/dataset/doi:10.5061%2Fdryad.mcvdnck22

Citation: Bjerager, Jakob (2021), Long-term development of lens fluorescence in a twin cohort: Heritability and effects of age and lifestyle, Dryad, Dataset, https://doi.org/10.5061/dryad.mcvdnck22


Abstract
Background: The blue-green autofluorescence of the ocular lens increases with age, glycemia and smoking, as the irreplaceable structural proteins of the lens slowly accumulate damage from the encounter with reactive molecular species. We have conducted a prospective study of lens autofluorescence over two decades in a twin cohort.

Methods: The study included 131 phakic, non-diabetic adult twins (median age at follow-up 58 years, range 41-66 years) who were examined twice at an interval of 21 years. Change in anterior lens peak autofluorescence was analyzed in relation to age, current and baseline glycemia, cumulative smoking and heritability.

Results: The level of lens autofluorescence in the study population increased as a function of age and smoking (p ≤.002), but not as a function of glycemia (p ≥.069). Lens autofluorescence remained a highly heritable trait (90.6 % at baseline and 93.3 % at follow-up), but whereas the combined effect of age and cumulative smoking explained 57.2 % of the variance in lens autofluorescence at baseline in mid-life, it only accounted for 31.6 % at follow-up 21 years later.

Conclusion: From mid to late adulthood, the level of blue-green fluoescence remained overwhelmingly heritable, but became less predictable from age, smoking habits and glycemic status. Presumably, as the lens ages, its intrinsic characteristics come to dominate over environmental and systemic factors, perhaps in a prelude to the development of cataract.

Methods
Statistical analysis

Statistical analyses were performed in R-Studio v1.2.5001 for Windows. Normality was tested by Shapiro-Wilk normality test. Parametric data were reported in means with 95 % confidence intervals or standard deviations (SD) and compared using Student’s t-test. Non-parametric variables were reported in medians and interquartile ranges (IQR) and/or full ranges and compared using the Mann-Whitney U test. Lens fluorescence was transformed by log10 to obtain normal distributions in all analyses. All lens fluorescence values reported have been back-transformed by antilog to geometric means with 95 % confidence intervals.

Univariate and multivariable log-level linear mixed model analyses adjusted for twin-pair data clustering were performed with the R functions ‘lmer’ (lme4 v.1.1.26 package) and ‘modelTest’ (JWileymisc v. 1.2.0 package) with adjusted R2 values reported, and coefficient estimates exponentiated and converted to percentages to designate the percentage increase in median lens fluorescence per one-unit increase in each covariate. Only covariates with statistically significant influence on lens fluorescence as found by univariate analysis were included in the corresponding multivariable analyses.

Broad-sense heritability analyses of lens fluorescence were performed with the R function ‘twinlm’ (mets v. 1.2.8.1 package) with adjustment for covariates that were found to have statistically significant effects on lens fluorescence in univariate linear regression analyses. Heritability and environmental influences were quantified into the coefficients A (additive genetics), D (dominant genetics), C (shared environment) and E (non-shared environment) and the broad-sense heritability coefficient h2  (A+D), calculated in each of the following combinatory heritability models: ACE, ADE, AE, DE and CE. Best-fitting heritability models were found by Akaike’s information criterion (AIC), with the lowest AIC-value defining the best-fitting model in each analysis group. Models with AIC-values between the value of the best fitting model and the value of the best fitting model plus two AIC-units were considered statistically non-inferior to the best fitting model. P-values below 5 % were considered statistically significant in all analyses.

Usage Notes
Please view the spreadsheet tab "ReadMe_tab" of the data file for usage notes. 