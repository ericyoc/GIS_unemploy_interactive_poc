# Geographic Information Systems (GIS) Maps

This Python script creates an interactive visualization of unemployment data for Washington and California State counties. It combines geographical data with unemployment statistics to produce a choropleth map and a detailed table.

## Interactive Map - Washington State Unemployment by County
![](https://github.com/ericyoc/WA_unemploy_interactive_poc/blob/main/wa_state_unemploy_interactive_map.jpg)


## Interactive Map - Califorina State Unemployment by County
![](https://github.com/ericyoc/WA_unemploy_interactive_poc/blob/main/ca_state_unemploy_interactive_map.jpg)

## Features

- Interactive choropleth map of State counties
- Detailed table of unemployment statistics
- Data from May 2024 (projected)

## How It Works

1. **Data Retrieval:**
   - WA and CA Geographical data: Downloaded from the US Census Bureau
   - WA and CA Unemployment data: Fetched from the State Employment Security Department

2. **Data Processing:**
   - County names are normalized and matched between datasets
   - Unemployment rates are calculated and rounded to two decimal places

3. **Visualization:**
   - A choropleth map is created using Plotly, showing unemployment rates by county
   - A table is generated displaying detailed statistics for each county

## Dependencies

- geopandas
- pandas
- plotly
- requests

## Data Sources

- WA and CA Geographical Data: [US Census Bureau TIGER/Line Shapefiles](https://www2.census.gov/geo/tiger/TIGER2023/COUNTY/tl_2023_us_county.zip)
- WA Unemployment Data: [Washington State Employment Security Department](https://media.esd.wa.gov/esdwa/Default/ESDWAGOV/labor-market-info/Libraries/Regional-reports/LAUS/Unemployment%20Statistics%20by%20County%20-%20May%202024.xlsx)
- CA Unemployment Data: (https://labormarketinfo.edd.ca.gov/data/interactive-labor-market-data-tools.html)

## Usage

1. Ensure all dependencies are installed
2. Run the script:
3. The script will generate an interactive plot in your default web browser

## Output

- An interactive Plotly figure with two components:
1. A choropleth map of State, color-coded by unemployment rate
2. A table listing detailed unemployment statistics for each county

## Note

The unemployment data is projected for May 2024. Actual data may vary when available.

## Disclaimer

The Python code is for research and educational purposes only.

## License
Copyright 2024 Eric Yocam

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
