# EPS variance
This workbook analyzing Zack's `earning surprise` and `earnings pre-announcement` data to calculate the accuracy of company guidance relative to actual quarterly EPS results.  We use the free-tier sample data to rank companies in the sample by their forecast accuracy and get the following results:

| company_name    | avg_fcst_err | fcst_rank |
|:----------------|-------------:|----------:|
| CATERPILLAR INC |    0.0074627 |         1 |
| WALMART INC     |    0.0314371 |         2 |
| CISCO SYSTEMS   |    0.0352750 |         3 |
| PROCTER & GAMBL |    0.0682777 |         4 |
| APPLE INC       |    0.0883720 |         5 |
| UTD TECHS CORP  |    0.0890505 |         6 |
| DU PONT (EI) DE |    0.0933152 |         7 |
| MERCK & CO INC  |    0.0941176 |         8 |
| INTEL CORP      |    0.1209685 |         9 |

The transformed dataset used for the ranking is contained in `quandl_eps_analysis.xlsx`.
