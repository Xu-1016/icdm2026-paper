# Paired Matched Terminal Supervision and Direction-Gain Allocation for Budgeted Sample-Column Interventions

Zhuoyang Xu¹, Pingrui Lai², Yizhuo Tian², Hua Yang²*

¹ Shanghai Shixi High School, Shanghai, China  
² Shanghai Jiao Tong University, Shanghai, China  
* Corresponding author

**Paper ID: S30334**  
IEEE International Conference on Data Mining (ICDM 2026), Shenyang, China

**Paper webpage:** https://xu-1016.github.io/icdm2026-paper/

**Files:** [Paper (PDF)](paper.pdf) | [Conference poster (PDF)](Poster.pdf)

## Abstract

Tabular models can use schema information, such as column names and data types, to interpret cell values, yet a uniform schema-semantic strategy may not benefit all samples equally. Under a limited intervention budget, sample-column interventions require within-sample action selection and cross-row budget allocation, but reliable supervision for estimating incremental value is lacking. We introduce Paired matched terminal supervision, deriving intervention credit from matched terminal outcomes: PairedMagnitude preserves continuous gain, whereas PairedSign preserves beneficial direction. Sign-to-Magnitude uses PairedSign for within-row candidate selection and a PairedMagnitude estimator for cross-row allocation. In the main supervision comparison, PairedMagnitude achieves the highest mean Gain at all seven budgets, reaching 0.003256 at five percent. At five percent under dataset-equal aggregation, Sign-to-Magnitude achieves higher mean Gain and F1 change than Sign-only and, relative to Magnitude-only, lower Harm of 29.86 percent versus 42.98 percent and higher mean F1 change of 0.001606 versus 0.001000, despite lower mean Gain. These results support the value of matched intervention credit and stage-specific use of direction and magnitude information.

**Keywords:** paired supervision, matched terminal supervision, budgeted intervention, sample-column ranking, Sign-to-Magnitude
