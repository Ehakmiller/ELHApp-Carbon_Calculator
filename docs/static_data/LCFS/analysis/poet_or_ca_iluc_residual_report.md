# POET OR-to-CA ILUC Residual Analysis

Residual = (OR CI + 12.25) - CA CI. A residual near zero means the OR-to-CA spread is explained by the assumed ILUC bridge.

Matched POET corn-starch pathway rows: 12; facilities: 8.

## Ranked Residual Table

| facility | city | state | coproduct | or_ci | ca_ci | or_minus_ca_spread | expected_spread | residual_ci | total_btu_per_gal | chp_status | corn_fiber_technology_status | d3_capability | year_built | capacity_mgy | dryer_type | natural_gas_source | outlier_group |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Poet Biorefinning-Coon Rapids | Coon Rapids | IA | WDGS | 62.64 | 66.28 | -3.64 | 12.25 | 8.61 | 23063.24 |  | BPX | Yes | 2002.00 | 65.00 | Ring Dryer | Natural Gas | iowa_outlier |
| Poet Biorefinning-Jewell LLC | Jewell | IA | WDGS | 62.32 | 67.19 | -4.87 | 12.25 | 7.38 | 23426.32 | CHP | BPX | Yes | 2006.00 | 90.00 | Ring Dryer | Natural Gas | iowa_outlier |
| Poet Biorefinning-Corning LLC | Corning | IA | WDGS | 60.92 | 66.57 | -5.65 | 12.25 | 6.60 | 23041.57 | CHP | BPX | Yes | 2007.00 | 90.00 | Ring Dryer | Natural Gas | iowa_outlier |
| Poet Biorefining- Big Stone LLC | Big Stone City | SD | DDGS | 64.15 | 75.07 | -10.92 | 12.25 | 1.33 | 17331.24 | CHP | BPX | Yes | 2002.00 | 105.00 | Ring Dryer | Natural Gas | other_poet |
| Poet Biorefining- Hudson | Hudson | SD | DDGS | 62.99 | 73.94 | -10.95 | 12.25 | 1.30 | 23497.18 | CHP | BPX | Yes | 2004.00 | 80.00 | Ring Dryer | Natural Gas | other_poet |
| Poet Biorefining- Mitchell LLC | Mitchell | SD | WDGS | 55.03 | 66.07 | -11.04 | 12.25 | 1.21 | 23612.57 |  | BPX | Yes | 2006.00 | 86.00 | Ring Dryer | Natural Gas | other_poet |
| Poet Biorefining- Mitchell LLC | Mitchell | SD | DDGS | 62.55 | 73.69 | -11.14 | 12.25 | 1.11 | 23612.57 |  | BPX | Yes | 2006.00 | 86.00 | Ring Dryer | Natural Gas | other_poet |
| Poet Biorefining- Big Stone LLC | Big Stone City | SD | WDGS | 56.72 | 67.98 | -11.26 | 12.25 | 0.99 | 17331.24 | CHP | BPX | Yes | 2002.00 | 105.00 | Ring Dryer | Natural Gas | other_poet |
| Poet Biorefining- Hudson | Hudson | SD | WDGS | 55.27 | 66.79 | -11.52 | 12.25 | 0.73 | 23497.18 | CHP | BPX | Yes | 2004.00 | 80.00 | Ring Dryer | Natural Gas | other_poet |
| Poet Biorefining- Chancellor LLC | Chancellor | SD | DDGS+WDGS | 51.02 | 62.63 | -11.61 | 12.25 | 0.64 | 9377.22 | CHP | BPX | Yes | 2003.00 | 125.00 | Ring Dryer | Biogas | other_poet |
| Poet Biorefining- Groton LLC | Groton | SD | WDGS | 56.16 | 68.73 | -12.57 | 12.25 | -0.32 | 24353.60 |  | BPX | Yes | 2005.00 | 68.00 | Ring Dryer | Natural Gas | other_poet |
| Poet Biorefining- Groton LLC | Groton | SD | DDGS | 63.41 | 75.67 | -12.26 | 12.25 | -0.01 | 24353.60 |  | BPX | Yes | 2005.00 | 68.00 | Ring Dryer | Natural Gas | other_poet |


## Correlations With Residual

| variable | n | unique_values | correlation_with_residual |
| --- | --- | --- | --- |
| total_btu_per_gal | 12 | 8 | 0.2075 |
| year_built | 12 | 6 | 0.1067 |
| capacity_mgy | 12 | 7 | -0.1676 |
| chp_flag | 12 | 2 | 0.0972 |
| fiber_flag | 12 | 1 |  |
| d3_flag | 12 | 1 |  |
| natural_gas_flag | 12 | 2 | 0.1838 |


## BTU Regression

Pathway-level: n=12, slope=0.144 residual CI per 1,000 BTU/gal, R²=0.043.

Facility-average: n=8, slope=0.232 residual CI per 1,000 BTU/gal, R²=0.113.


## Group Summaries

| grouping | bucket | pathway_count | facility_count | avg_residual | median_residual | avg_btu | avg_or_ci | avg_ca_ci |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| outlier_group | other_poet | 9 | 5 | 0.78 | 0.99 | 20774.04 | 58.59 | 70.06 |
| outlier_group | iowa_outlier | 3 | 3 | 7.53 | 7.38 | 23177.04 | 61.96 | 66.68 |
| chp_status | CHP | 7 | 5 | 2.71 | 1.30 | 19643.14 | 59.06 | 68.60 |
| chp_status | blank | 5 | 3 | 2.12 | 1.11 | 23799.11 | 59.96 | 70.09 |
| fiber_technology | BPX | 12 | 8 | 2.46 | 1.16 | 21374.79 | 59.43 | 69.22 |
| d3_capability | Yes | 12 | 8 | 2.46 | 1.16 | 21374.79 | 59.43 | 69.22 |
| dryer_type | Ring Dryer | 12 | 8 | 2.46 | 1.16 | 21374.79 | 59.43 | 69.22 |
| natural_gas_source | Natural Gas | 11 | 7 | 2.63 | 1.21 | 22465.48 | 60.20 | 69.82 |
| natural_gas_source | Biogas | 1 | 1 | 0.64 | 0.64 | 9377.22 | 51.02 | 62.63 |


## Conclusion

The Iowa outliers remain anomalous after the 12.25 CI ILUC bridge. Their average residual is 7.53, versus 0.78 for the rest of the matched POET pathways. That means OR+12.25 overstates the comparable CA CI for Coon Rapids, Jewell, and Corning by roughly 6.6 to 8.6 CI points, while the normal POET group is close to zero residual.

Thermal BTU/gal does not explain much of the remaining variance: pathway-level R² is 0.043 and facility-average R² is 0.113. Fiber technology and D3 status have no useful explanatory power here because all matched POET rows carry the same BPX/Yes indicators; dryer type is also constant as Ring Dryer. CHP and gas source split the sample, but the three anomalous Iowa rows are not uniquely identified by either field.
