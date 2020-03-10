# GeminiTEXES2017
Repository for retrieval products from Gemini TEXES 2017 observations of Jupiter.  These data have been submitted for publication to JGR-Planets:

Fletcher et al. (2020), Jupiter's Equatorial Plumes and Hot Spots:  Spectral Mapping from Gemini/TEXES and Juno/MWR, JGR-Planets, submitted.

The directory structure is as follows:

* AmateurData:  Contains figures showing the tracking of NEB hot spots via both JUPOS (visible-light) and IRTF (5-µm) observations.  Maps of amateur data corresponding to Juno perijoves 3-8 are contained in `Maps4Juno`; maps of amateur data corresponding to TEXES observations in 2017 are contained in `Maps4TEXES.`

* GreatRedSpot:  Gemini/TEXES retrievals of temperatures, aerosols, ammonia, phosphine, ethane, acetylene from March 2017.  EPS, JPEG, and IDL 'sav' files are all provided, as well as a text file 'grs_TNH3.dat' containing the results for temperatures and ammonia as a function of latitude, longitude, and pressure.

* SEBOutbreak:  As for the 'GreatRedSpot' directory, but for a major outbreak of convective activity in the South Equatorial Belt.

* MWRObservations:  Figures showing the zonally-averaged MWR observations from PJ3-9 in all six channels.  In addition, simulated MWR brightness in channels 5&6 are included, based on retrievals from Gemini/TEXES observations in 2017 (see main paper).

* NEBMaps:  Gemini/TEXES retrieval products for Jupiter's tropical domain, including  temperatures, aerosols, ammonia, phosphine, ethane, acetylene from March 2017.  Each sub-directory is for one of the seven groups of TEXES observations (i.e., a retrieval spanning 50 degrees of longitude from spectral cubes acquired within ~75 minutes).  EPS, JPEG, and IDL 'sav' files are all provided.  

* TEXESdata:  Cylindrical projections of TEXES observations in each spectral setting, both as combined maps in `CylindricalMaps`, and as individual groups in `TEXESGroups.`  Note that the raw TEXES observations can be downloaded here:  https://doi.org/10.5281/zenodo.3702328

* ZonalResults:  Results from zonal-mean retrievals for each of the seven TEXES groups.  We include both level-1 retrieval products (temperatures, ammonia, phosphine, aerosols, ethane, acetylene) and level-2 derived products (windshear, thermal wind, density, para-hydrogen, heat capacity, buoyancy frequency, potential vorticity gradients).  EPS files, text files, and IDL 'sav' files are all provided.

* IRTFSpeX:  Cylindrical projections of the 2016-17 record of IRTF/SpeX observations used to track the 5-micron hot spots.
