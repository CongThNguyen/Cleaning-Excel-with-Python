# Cleaning-Excel-with-Python
Short project (using Python) to demonstrate my skill in data cleaning, merging and filter from Excel file. 

1. There are two files: `“GDP data Raw.xlsx” and “Brand Awareness.xlsx”`. Using pandas, and/or a selection of other packages:

a/ write python code to clean the two sets of data so that:

For `“GDP data Raw.xlsx”`, only the following columns are shown: 
   * `i`.	 'RPI', 
   * `ii`.	 'RPIX', 
   * `iii`.	 'RPI - Motoring Expenditure - Petrol (& oil)',
   * `iv`.	 'RPI - Fuel (& light)',
   * `v`.	 'RPI - Housing Costs',
   * `vi`.	 'CPI', 
   * `vii`.	'CPIH'. 

For `“Brand Awareness.xlsx”`, only the following columns are shown:
  * `i`. Spontaneous Brand Awareness , 
  * `ii`. Brand Consideration, 
  * `iii`. Fibre awareness (prompted),
  * `iv`.	Fibre Consideration,
  * `v`.TV awareness (prompted),
  * `vi`. TV consideration 

b/ Filter dates to be to contain up to and including `'2017-04-01' – ‘2018-10-01’` 

c/ Join the two dataset `“GDP data Raw.xlsx”` and `“Brand Awareness.xlsx”` by date. Then output to look like `"Metrics_combined.csv"`

2. The third file is called `‘Impressions & Clicks.xlsx’` which contains a websites clicks and impressions which is currently in a daily view format.

a/ Aggregate this data up to a weekly view, with weeks being Monday - Sunday. Then output to look like `"Impressions & clicks cleaned.csv"`

