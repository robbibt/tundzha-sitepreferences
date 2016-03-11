# tundzha_sitepreferences
Outputs of archaeological site preference analysis for the Upper Tundzha valley, Bulgaria

![Upper Tundzha Valley study region](https://github.com/robbibt/tundzha_sitepreferences/blob/master/study_area.png "Upper Tundzha Valley study region")


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

<br>

### Catchments used for site catchment analysis
Calculated using an anisotropic movement model based on Tobler’s Hiking function (Tobler 1993)

| Catchment               | Abbreviation | Utility                                                                                                                                                     | Radius calculation                                          | 
|-------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------| 
| Immediate site area     | ISA          | Study of factors influencing the specific location of an archaeological site, rather than its overall position in the wider landscape                       | Median radius (in minutes) of TRAP sites                    | 
| Intensive activity area (3.3 min) | IAA          | Zone of intensive land-use expected in the immediate surrounds of an archaeological site, potentially related to intense arable agriculture or horticulture | Radius of most intense pottery sherd clustering (Moran’s I) | 
| Extensive activity area (13.3 min) | EAA          | Influence of a site’s extended landscape, potentially related to extensive agriculture, herding and pastoralism (Ullah, 2011)                               | Radius of maximum pottery sherd clustering (Moran’s I)      | 

<br>

### Socio-environmental variables
Variables were selected for their potential strategic, agricultural, pastoral, cultural and aesthetic, transport and taphonomic influence on archaeological distribution patterns in the Upper Tundzha. Each variable was extracted using at least one of three unique site catchment radii: immediate site area (ISA), intensive activity area (IAA) and extensive activity area (EAA).

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

<br>

### References

<sup>Alexakis, Dimitrios, Apostolos Sarris, Theodoros Astaras, and Konstantinos Albanakis. 2011. “Integrated GIS, Remote Sensing and Geomorphologic Approaches for the Reconstruction of the Landscape Habitation of Thessaly during the Neolithic Period.” Journal of Archaeological Science 38 (1). Elsevier Ltd: 89–100. doi:10.1016/j.jas.2010.08.013.

<sup>Arnold, Elizabeth R, and Haskel J Greenfield. 2006. “The Origins of Transhumant Pastorialism in Temperate South Eastern Europe: A Zooarchaeological Perspective from the Central Balkans.”

<sup>Brandt, Roel, Bert J Groenewoudt, and Kenneth L Kvamme. 1992. “An Experiment in Archaeological Site Location: Modeling in the Netherlands Using GIS Techniques.” World Archaeology 24 (2): 268–82.

<sup>Carleton, W Chris, James Conolly, and Gyles Ianonne. 2012. “A Locally-Adaptive Model of Archaeological Potential (LAMAP).” Journal of Archaeological Science 39 (11). Elsevier Ltd: 3371–85. doi:10.1016/j.jas.2012.05.022.

<sup>Dennell, Robin W, and D Webley. 1975. “Prehistoric Settlement and Land Use in Southern Bulgaria.” In Palaeoeconomy, edited by E. S. Higgs, 97–109. London and New York: Cambridge University Press.

<sup>Dorshow, Wetherbee Bryan. 2012. “Modeling Agricultural Potential in Chaco Canyon during the Bonito Phase: A Predictive Geospatial Approach.” Journal of Archaeological Science 39 (7). Elsevier Ltd: 2098–2115. doi:10.1016/j.jas.2012.02.004.

<sup>Espa, G., R. Benedetti, A. De Meo, U. Ricci, and S. Espa. 2006. “GIS Based Models and Estimation Methods for the Probability of Archaeological Site Location.” Journal of Cultural Heritage 7 (3): 147–55. http://linkinghub.elsevier.com/retrieve/pii/S1296207406000446.

<sup>Garcia, Alejandro. 2012. “GIS-Based Methodology for Palaeolithic Site Location Preferences Analysis. A Case Study from Late Palaeolithic Cantabria (Northern Iberian Peninsula).” Journal of Archaeological Science 40 (1). Elsevier Ltd: 217–26. doi:10.1016/j.jas.2012.08.023.

<sup>Graves, Dorothy. 2011. “The Use of Predictive Modelling to Target Neolithic Settlement and Occupation Activity in Mainland Scotland.” Journal of Archaeological Science 38 (3). Elsevier Ltd: 633–56. doi:10.1016/j.jas.2010.10.016.

<sup>Jarosław, Jasiewicz, and Iwona Hildebrandt-Radke. 2009. “Using Multivariate Statistics and Fuzzy Logic System to Analyse Settlement Preferences in Lowland Areas of the Temperate Zone: An Example from the Polish Lowlands.” Journal of Archaeological Science 36 (10): 2096–2107. doi:10.1016/j.jas.2009.06.004.

<sup>Kosiba, Steve, and Andrew M Bauer. 2012. Mapping the Political Landscape: Toward a GIS Analysis of Environmental and Social Difference. Journal of Archaeological Method and Theory. Vol. 20. doi:10.1007/s10816-011-9126-z.

<sup>Kvamme, Kenneth L. 1992. “A Predictive Site Location Model on the High Plains: An Example with an Independent Test.” Plains Anthropologist 37 (138): 19–40.

<sup>Llobera, Marcos. 2001. “Building Past Landscape Perception with GIS: Understanding Topographic Prominence.” Journal of Archaeological Science 28 (9): 1005–14. doi:10.1006/jasc.2001.0720.

<sup>Llobera, Marcos, P Fábrega-Álvarez, and C Parcero-Oubiña. 2011. “Order in Movement: A GIS Approach to Accessibility.” Journal of Archaeological Science 38 (4): 843–51.

<sup>Madzharov, Mitko. 2009. Roman Roads in Bulgaria: Contribution to the Development of Roman Road System in the Provinces of Moesia and Thrace. Veliko Tŭrnovo: Faber.

<sup>Ogburn, Dennis E. 2006. “Assessing the Level of Visibility of Cultural Objects in Past Landscapes.” Journal of Archaeological Science 33 (3): 405–13. doi:10.1016/j.jas.2005.08.005.

<sup>Sobotkova, Adela. 2012. The Valley of the Kings? Social Complexity of Inland Thrace during the First Millennium BC. University of Michigan (PhD dissertation).

<sup>Vanacker, Veerle, Gerard Govers, Philip van Peer, Cyriel Verbeek, Johan Desmet, and Jeroen Reyniers. 2001. “Using Monte Carlo Simulation for the Environmental Analysis of Small Archaeologic Datasets, with the Mesolithic in Northeast Belgium as a Case Study.” Journal of Archaeological Science 28 (6): 661–69. doi:10.1006/jasc.2001.0654.

<sup>Vaughn, Sallie, and Tom Crawford. 2009. “A Predictive Model of Archaeological Potential: An Example from Northwestern Belize.” Applied Geography 29 (4). Elsevier Ltd: 542–55. doi:10.1016/j.apgeog.2009.01.001.

<sup>Warren, Robert E. 1990. “Predictive Modelling of Archaeological Site Location: A Case Study in the Midwest.” In Interpreting Space: GIS and Archaeology, edited by K.M.S. Allen, S.W. Green, and E.B.W. Zubrow, 201–15. London: Taylor & Francis.

<sup>White, Devin A., and Sarah B. Barber. 2012. “Geospatial Modeling of Pedestrian Transportation Networks: A Case Study from Precolumbian Oaxaca, Mexico.” Journal of Archaeological Science 39 (8): 2684–96. doi:10.1016/j.jas.2012.04.017.

<sup>Witt, Matthias, Maik Evers, M Möller, and Christian Dette. 2012. “Characterization and Analysis of Natural Resource Potentials for Archaeological Site Location Using the Example of the Early Bronze Age in Central Germany.” Journal for Ancient Studies 3: 347–52. http://journal.topoi.org/index.php/etopoi/article/download/133/158.

