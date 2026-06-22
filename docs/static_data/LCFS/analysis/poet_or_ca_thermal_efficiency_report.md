# POET OR-to-CA Thermal Efficiency Analysis

Source matched corn pathway rows: 12; facilities: 8

## Correlations

| x | y | n | correlation |
| --- | --- | --- | --- |
| total_btu_per_gal | ca_ci | 12 | 0.34 |
| total_btu_per_gal | or_ci | 12 | 0.49 |
| total_btu_per_gal | or_minus_ca_spread | 12 | 0.21 |


## Regression: OR-minus-CA Spread vs Total BTU/gal

Pathway-level n=12, slope=0.144 CI per 1,000 BTU/gal, R²=0.043.

Facility-average n=8, slope=0.232 CI per 1,000 BTU/gal, R²=0.113.


## Outlier vs Normal POET Group

| outlier_group | pathway_count | facility_count | avg_btu | avg_or_ci | avg_ca_ci | avg_or_minus_ca_spread | median_or_minus_ca_spread |
| --- | --- | --- | --- | --- | --- | --- | --- |
| normal_poet_group | 9 | 5 | 20774.04 | 58.59 | 70.06 | -11.47 | -11.26 |
| outlier | 3 | 3 | 23177.04 | 61.96 | 66.68 | -4.72 | -4.87 |


## BTU Bucket Summary

| btu_bucket | pathway_count | facility_count | avg_btu | avg_or_ci | avg_ca_ci | avg_or_minus_ca_spread | median_or_minus_ca_spread | min_spread | max_spread |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 24,000-26,000 | 2 | 1 | 24353.60 | 59.78 | 72.20 | -12.42 | -12.42 | -12.57 | -12.26 |
| <24,000 | 10 | 7 | 20779.03 | 59.36 | 68.62 | -9.26 | -10.99 | -11.61 | -3.64 |


## Ranked by BTU/gal

| facility | city | state | coproduct | or_ci | ca_ci | or_minus_ca_spread | total_btu_per_gal | natural_gas_source | dryer_type | chp_status | corn_fiber_technology_status | d3_capability | capacity_mgy | year_built |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Poet Biorefining- Chancellor LLC | Chancellor | SD | DDGS+WDGS | 51.02 | 62.63 | -11.61 | 9377.22 | Biogas | Ring Dryer | CHP | BPX | Yes | 125.00 | 2003.00 |
| Poet Biorefining- Big Stone LLC | Big Stone City | SD | DDGS | 64.15 | 75.07 | -10.92 | 17331.24 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 105.00 | 2002.00 |
| Poet Biorefining- Big Stone LLC | Big Stone City | SD | WDGS | 56.72 | 67.98 | -11.26 | 17331.24 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 105.00 | 2002.00 |
| Poet Biorefinning-Corning LLC | Corning | IA | WDGS | 60.92 | 66.57 | -5.65 | 23041.57 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 90.00 | 2007.00 |
| Poet Biorefinning-Coon Rapids | Coon Rapids | IA | WDGS | 62.64 | 66.28 | -3.64 | 23063.24 | Natural Gas | Ring Dryer |  | BPX | Yes | 65.00 | 2002.00 |
| Poet Biorefinning-Jewell LLC | Jewell | IA | WDGS | 62.32 | 67.19 | -4.87 | 23426.32 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 90.00 | 2006.00 |
| Poet Biorefining- Hudson | Hudson | SD | DDGS | 62.99 | 73.94 | -10.95 | 23497.18 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 80.00 | 2004.00 |
| Poet Biorefining- Hudson | Hudson | SD | WDGS | 55.27 | 66.79 | -11.52 | 23497.18 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 80.00 | 2004.00 |
| Poet Biorefining- Mitchell LLC | Mitchell | SD | DDGS | 62.55 | 73.69 | -11.14 | 23612.57 | Natural Gas | Ring Dryer |  | BPX | Yes | 86.00 | 2006.00 |
| Poet Biorefining- Mitchell LLC | Mitchell | SD | WDGS | 55.03 | 66.07 | -11.04 | 23612.57 | Natural Gas | Ring Dryer |  | BPX | Yes | 86.00 | 2006.00 |
| Poet Biorefining- Groton LLC | Groton | SD | DDGS | 63.41 | 75.67 | -12.26 | 24353.60 | Natural Gas | Ring Dryer |  | BPX | Yes | 68.00 | 2005.00 |
| Poet Biorefining- Groton LLC | Groton | SD | WDGS | 56.16 | 68.73 | -12.57 | 24353.60 | Natural Gas | Ring Dryer |  | BPX | Yes | 68.00 | 2005.00 |


## Ranked by OR-minus-CA Spread

| facility | city | state | coproduct | or_ci | ca_ci | or_minus_ca_spread | total_btu_per_gal | natural_gas_source | dryer_type | chp_status | corn_fiber_technology_status | d3_capability | capacity_mgy | year_built |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Poet Biorefining- Groton LLC | Groton | SD | WDGS | 56.16 | 68.73 | -12.57 | 24353.60 | Natural Gas | Ring Dryer |  | BPX | Yes | 68.00 | 2005.00 |
| Poet Biorefining- Groton LLC | Groton | SD | DDGS | 63.41 | 75.67 | -12.26 | 24353.60 | Natural Gas | Ring Dryer |  | BPX | Yes | 68.00 | 2005.00 |
| Poet Biorefining- Chancellor LLC | Chancellor | SD | DDGS+WDGS | 51.02 | 62.63 | -11.61 | 9377.22 | Biogas | Ring Dryer | CHP | BPX | Yes | 125.00 | 2003.00 |
| Poet Biorefining- Hudson | Hudson | SD | WDGS | 55.27 | 66.79 | -11.52 | 23497.18 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 80.00 | 2004.00 |
| Poet Biorefining- Big Stone LLC | Big Stone City | SD | WDGS | 56.72 | 67.98 | -11.26 | 17331.24 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 105.00 | 2002.00 |
| Poet Biorefining- Mitchell LLC | Mitchell | SD | DDGS | 62.55 | 73.69 | -11.14 | 23612.57 | Natural Gas | Ring Dryer |  | BPX | Yes | 86.00 | 2006.00 |
| Poet Biorefining- Mitchell LLC | Mitchell | SD | WDGS | 55.03 | 66.07 | -11.04 | 23612.57 | Natural Gas | Ring Dryer |  | BPX | Yes | 86.00 | 2006.00 |
| Poet Biorefining- Hudson | Hudson | SD | DDGS | 62.99 | 73.94 | -10.95 | 23497.18 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 80.00 | 2004.00 |
| Poet Biorefining- Big Stone LLC | Big Stone City | SD | DDGS | 64.15 | 75.07 | -10.92 | 17331.24 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 105.00 | 2002.00 |
| Poet Biorefinning-Corning LLC | Corning | IA | WDGS | 60.92 | 66.57 | -5.65 | 23041.57 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 90.00 | 2007.00 |
| Poet Biorefinning-Jewell LLC | Jewell | IA | WDGS | 62.32 | 67.19 | -4.87 | 23426.32 | Natural Gas | Ring Dryer | CHP | BPX | Yes | 90.00 | 2006.00 |
| Poet Biorefinning-Coon Rapids | Coon Rapids | IA | WDGS | 62.64 | 66.28 | -3.64 | 23063.24 | Natural Gas | Ring Dryer |  | BPX | Yes | 65.00 | 2002.00 |


## Conclusion
Thermal BTU/gal does not appear to explain the smaller spreads at Coon Rapids, Jewell, and Corning. Those outliers are not lower-BTU facilities in the available data; they sit in the highest BTU bucket, while several lower-BTU POET facilities show the normal roughly -11 to -13 CI spread.
