## LEDD Scripts

### ledd calculator

1. Export the instrument "PD Medications - LED Calculation" from Z1XADRCNACC Database as a CSV file (raw labels).
2. Update paths.yaml file with your desired input (location of your saved PD Medications export) and output (calculated ledd data) file paths.

### ledd cleaner

- required input files:  
  1. `raw Z1XADRCNACC export`  
  2. `subject list of adrc_id's of interest`
- exports cleaned ledd dataframe with only subjects of interest


