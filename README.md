## Minnesota Legislative Coordinating Commission
### Data Repository

### What's included?
- Data (GeoJSON)
  -statewide
    - Minnesota Senate Districts
    - Minnesota House Districts
    - Minnesota Congressional Districts
  -county
    - [county]
      - precincts (2015 voting tabulation districts)

### Repository as RESTful API
- For statewide data:
`https://raw.githubusercontent.com/LegislativeCoordinatingCommissionGIS/Data/master/statewide/[dataset].geojson`


- For chunks of larger datasets
`https://raw.githubusercontent.com/LegislativeCoordinatingCommissionGIS/Data/master/[geography]/ [subgeography]/[dataset].geojson`
  - where [geographic area] can be 'statewide', 'county', 


- Embed map on other sites:

`<script src="https://embed.github.com/view/geojson/LegislativeCoordinatingCommissionGIS/Data/ master/<path_to_file>"></script>`

EX: `<script src = "https://embed.github.com/view/geojson/LegislativeCoordinatingCommissionGIS/Data/master/statewide/MnHouse-2012.geojson">
  </script>`
  - By default, the embedded map is 420px X 620px, but you can customize the output by passing height and width variables as parameters at the end, such as ?height=300&width=500.
  - See https://help.github.com/articles/mapping-geojson-files-on-github/ for more details on embedding maps on your website.
