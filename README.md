# tundzha_sitepreferences
Outputs of archaeological site preference analysis for the Upper Tundzha valley, Bulgaria



### Archaeological periods 
Timespans for the Upper Tundzha Valley study region after Sobotkova (2012)

| Time-span     | Archaeological period / dataset     | Abbreviation | Sites (total) | Sites (study) | 
|---------------|-------------------------------------|--------------|---------------|---------------| 
| 6000-3100 BC  | Prehistoric period                  | APH          | 19            | 13            | 
| 3101-2400 BC  | Early Bronze Age                    | EBA          | 15            | 10            | 
| 2501-1600 BC  | Middle Bronze Age                   | MBA          | 5             | 0             | 
| 1601-1000 BC  | Late Bronze Age                     | LBA          | 12            | 6             | 
| 1101-400 BC   | Early Iron Age                      | EIA          | 44            | 26            | 
| 401-100 BC    | Late Iron Age                       | LIA          | 50            | 32            | 
| 101 BC-300 AD | Roman period                        | RM           | 37            | 18            | 
| 3101-300 AD   | Burial mounds (undated; mostly LIA) | Mounds       | 784           | 302           |


### Catchments used for site catchment analysis
Calculated using an anisotropic movement model based on Tobler’s Hiking function (Tobler 1993)

| Catchment               | Abbreviation | Utility                                                                                                                                                     | Radius calculation                                          | 
|-------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------| 
| Immediate site area     | ISA          | Study of factors influencing the specific location of an archaeological site, rather than its overall position in the wider landscape                       | Median radius (in minutes) of TRAP sites                    | 
| Intensive activity area (3.3 min) | IAA          | Zone of intensive land-use expected in the immediate surrounds of an archaeological site, potentially related to intense arable agriculture or horticulture | Radius of most intense pottery sherd clustering (Moran’s I) | 
| Extensive activity area (13.3 min) | EAA          | Influence of a site’s extended landscape, potentially related to extensive agriculture, herding and pastoralism (Ullah, 2011)                               | Radius of maximum pottery sherd clustering (Moran’s I)      | 


### Socio-environmental variables

| Variable  | Category       | Data type    | Description                                       | References                                                                                                                                           | 
|-----------|----------------|--------------|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------| 
| elev_av   | Topographic    | Quantitative | Mean of elevation (metres ASL)                            | Espa et al. 2006; Graves 2011; Garcia 2012                                                                                                    | 
| aspect_av | Topographic    | Quantitative | Mean of aspect (degrees)                                  | Warren 1990; Kvamme 1992; Vanacker et al. 2001; Alexakis et al. 2011; Garcia 2012                                                           | 
| slope_av  | Topographic    | Quantitative | Mean of slope (degrees)                                   | Vanacker et al. 2001; Vaughn and Crawford 2009; Graves 2011; Carleton et al. 2012; Dorshow 2012                                             | 
| slope_sd  | Topographic    | Quantitative | Standard deviation of slope / terrain roughness (degrees) | Llobera et al. 2011; Garcia 2012                                                                                                               | 
| tpi_av    | Topographic    | Quantitative | Topographic prominence (TPI index)                        | Llobera 2001; Jarosław and Hildebrandt-Radke 2009; Graves 2011; Garcia 2012                                                                  | 
| solar_hr  | Topographic    | Quantitative | Solar radiation (hours sunlight)                          | Jarosław and Hildebrandt-Radke 2009; Garcia 2012                                                                                               | 
| soil_cf   | Soils/geology  | Quantitative | Soil coarse fraction (% coarse fraction)                  | Dennell and Webley 1975                                                                                                                         | 
| soil_col  | Soils/geology  | Categorical  | Dominant soil colour (Munsell colour class)               | Arnold and Greenfield 2006                                                                                                                      | 
| soil_tex  | Soils/geology  | Categorical  | Dominant soil texture (texture class)                     | Dennell and Webley 1975; Brandt et al. 1992; Vanacker et al. 2001; Carleton et al. 2012; Dorshow 2012                                       | 
| soil_div  | Soils/geology  | Categorical  | Soil texture diversity (texture classes)                  | Dennell and Webley 1975                                                                                                                         | 
| geol_un   | Soils/geology  | Categorical  | Dominant geological unit (unit)                           | Warren 1990; Espa et al. 2006                                                                                                                  | 
| geol_div  | Soils/geology  | Categorical  | Geological diversity (geological units)                   | Dennell and Webley 1975                                                                                                                         | 
| cti_av    | Hydrological   | Quantitative | Topographic wetness (CTI index)                           | Jarosław and Hildebrandt-Radke 2009; Vaughn and Crawford 2009; Witt et al. 2012                                                               | 
| dist_str  | Hydrological   | Quantitative | Distance to nearest watercourse (minutes)                 | Warren 1990; Brandt et al. 1992; Vanacker et al. 2001; Jarosław and Hildebrandt-Radke 2009; Vaughn and Crawford 2009; Carleton et al. 2012 | 
| cor_dir   | Transportation | Quantitative | Distance to transportation routes, direct to valley entrance/exit (cost-distance corridor)         | Madzharov 2009; Llobera et al. 2011; White and Barber 2012                                                                                    | 
| cor_seu   | Transportation | Quantitative | Distance to transportation routes, via Seuthopolis (cost-distance corridor)    | Madzharov 2009; Llobera et al. 2011; White and Barber 2012                                                                                    | 
| view_md   | Visibility     | Quantitative | Burial mound visibility (% visible mounds)               | Ogburn 2006; Alexakis et al. 2011                                                                                                              | 
| view_mt   | Visibility     | Quantitative | Mountains visibility (% visible mountain area)            | Graves 2011; Garcia 2012; Kosiba and Bauer 2012                                                                                               | 
| view_seu  | Visibility     | Quantitative | Seuthopolis visibility (% visible towers)                 | Ogburn 2006; Alexakis et al. 2011                                                                                                             | 
| view_val  | Visibility     | Quantitative | Valley floor visibility (% visible valley floor)          | Kvamme 1992; Graves 2011; Garcia 2012; Kosiba and Bauer 2012                                                                                 | 
