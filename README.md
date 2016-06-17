# d3map_NationalData
Fetch few years' data from china national data website, draw a map with d3js, dynamicly show the changes of the 10 years' data on map.
###############
release 1.0:
###############
seprated into 2 steps
1.get data from national
  get_reg_10_year_data_pools.ipynb  -- fetch data from china national data website, save into reg_10year.csv.
    take "Total Investment in Residential Buildings in the Whole Country" as example.
2. draw a map with d3 :[ refer to https://github.com/clemsos/d3-china-map ]
  cd d3map
  data from reg_10year.csv, 
  final result is  Investment10.html.
  - unsolved issue: 10 years data is not rolling in turn shown on map. only 1 year could be displayed.

