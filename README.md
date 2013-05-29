# lpfmpoints -  Evolution of LPFM Stations 

This time series visualization depicts approximate dates of U.S. Low Power FM stations going on the air along with milestones in the establishment and expansion of the LPFM service from 2000 to March 2011. 

To view the time series, [visit the gh-page][ghp] 

For more information about Low Power FM in the United States, please [visit the FCC page][lpfm].

## Purpose

This project is one of a number of visualization tools being investigated to communcate policy issues in new formats. This time series intends to display how the change in polices have allowed more Low Power FM stations to be established. Additional projects were developed in conjunction with this one:

* [LPFM Opportunities Spatial Analysis repo][lpfmrepo] 
* [LPFM Opportunities Map][lpfmmap]
* [LPFM Channel finder API][api]
  
## Data
  
  * Data are stored in [a cartoDB table][cartodb] 
  * /data directory also contains a copy of the source data in GeoJSON format (WGS 84) lpfm_points.geojson 
  
## Inspiration
  
Inspiration for this visualization comes from the Guardian UK’s [First World War Ship Movements][guk] and the good folks at [cartoDB][cdb] and their torque project. 
  
  [ghp]:http://fcc.github.com/lpfmpoints/lpfmpoint.html 
  [lpfm]: http://www.fcc.gov/encyclopedia/low-power-fm-broadcast-radio-stations-lpfm 
  [lpfmrepo]: https://github.com/FCC/lpfm
  [lpfmmap]: http://www.fcc.gov/maps/low_power_fm_opportunities_wo_2nd
  [api]: http://www.fcc.gov/developers/lpfm-api
  [cartodb]: https://fcc.cartodb.com/tables/lpfm_point/public
  [guk]: http://www.guardian.co.uk/news/datablog/interactive/2012/oct/01/first-world-war-royal-navy-ships-mapped 
  [cdb]: http://cartodb.com 
