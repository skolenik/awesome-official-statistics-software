## Awesome official statistics software [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
An awesome list of open source statistical software useful for creating and accessing official statistics.

#### An item on this list is awesome because it is
1. free, open source, and available for download and
2. used in the production of official statistics by at least one institute or provides access to official statistics.

We prefer software that is easy to install and use, has at least one stable version, and is actively maintained. [Contributions](#contributions) welcome.

#### News
- Dec 2017: List started during UNECE SDE 2017
- Jun 2019: Awesome list presented on **Modernstats World**: [slides](https://www.unece.org/fileadmin/DAM/stats/documents/ece/ces/ge.58/2019/mtg2/MWW2019_Soapbox_Netherlands_ten_Bosch.pdf)
- Dec 2019: **100  items on the list!!!**
- Dec 2020: Awesome list presented on **uRos2020**: [slides](https://r-project.ro/conference2020-presentations.html#Olav_TEN_BOSCH,_Mark_VAN_DER_LOO_and_Alexander_KOWARIK)
- Jan 2021: Awesome list in **[10th EG meeting on SDMX](https://www.imf.org/en/News/Seminars/Conferences/2021/01/25/10th-statistical-data-and-metadata-exchange)**: [slides](https://www.imf.org/-/media/Files/News/Seminars/2021/SDMX/siv-presentation-01-stocktaking-of-sdmx-tools.ashx)

#### Visuals
[![GSBPM use](viz/GSBPM_Small.png)](https://observablehq.com/@olavtenbosch/visualizing-awesomeofficialstatistics-org#GSBPM)
[![clickable version](viz/ClickableAwesomeSmall.png)](https://observablehq.com/@olavtenbosch/clickable-awesomeofficialstatistics-org)
[![word cloud](viz/wordCloudSmall.png)](https://observablehq.com/@olavtenbosch/visualizing-awesomeofficialstatistics-org#wordCloud)


*****

#### Design frame and sample ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 2.1)
- R package [SamplingStrata]( http://cran.stat.unipd.it/web/packages/SamplingStrata/index.html). Optimal Stratification of Sampling Frames for Multipurpose Sampling Surveys.
- R package [R2BEAT](https://cran.r-project.org/package=R2BEAT) Multistage Sampling Allocation and PSU Selection

#### Design variable descriptions ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 2.2)
- Excel [SDMX Matrix Generator](https://github.com/OECDSTD/sdmx-matrix-generator). Excel-based visual SDMX artefact authoring tool which generates SDMX-ML for upload into an SDMX repository such as a registry. By OECD.

#### Sampling ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 4.1)
- R package [sampling](https://CRAN.R-project.org/package=sampling). Several algorithms
for drawing (complex) survey samples and calibrating design weights.
- R package [surveyplanning](https://cran.r-project.org/package=surveyplanning). Tools for sample survey planning, including sample size calculation, estimation of expected precision for the estimates of totals, and calculation of optimal sample size allocation.


#### Scraping for Statistics ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 4.3)
- Java application [URLSearcher](https://github.com/SummaIstat/UrlSearcher). An application for searching Urls. Can be used to find websites of enterprise. By ISTAT.
- Java application [URLScorer](https://github.com/SummaIstat/UrlScorer). Gives a rule based score to scraped documents in a Solr database. By ISTAT.
- Node.js tool [RobotTool](https://github.com/SNStatComp/RobotTool). A tool for checking (price) changes on the web. By Statistics Netherlands.
- Python [Social-Media-Presence](https://github.com/jmaslankowski/WP2-Social-Media-Presence). A script for detecting social media presence on enterprises websites. By Statistics Poland.
- Python [Sustainability Reporting](https://github.com/AlessandraSozzi/MSc-dissertation). A script for measuring sustainability reporting from enterprises websites. By ONS.
- Python [urlfinding](https://github.com/SNStatComp/urlfinding). Software for finding websites of enterprises using a search engine and machine learning. By Statistics Netherlands


#### Process ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 5)
- R package [blaise](https://CRAN.R-project.org/package=blaise). Reading and writing Files in the Blaise Format from R. By Statistics Netherlands.
- Java application [Java-VTL](https://github.com/statisticsnorway/java-vtl). A partial implementation of the Validation Transformation Language, based on the VTL 1.1 draft specification. By Statistics Norway.
- Java application [ADaMSoft](http://adamsoft.sourceforge.net) implements procedures for data analysis, data, web and text mining. Also contains procedures for data validation and imputation, based on the principle of Fellegi and Holt.
- R package [dcmodify](https://CRAN.r-project.org/package=dcmodify). Derive new variables or modify data using externally defined data modification rules.

#### Data integration and record linkage ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 5.1)
- R package [reclin](https://cran.r-project.org/web/packages/reclin/index.html). Functions to assist in performing probabilistic record linkage and deduplication: generating pairs, comparing records, em-algorithm for estimating m- and u-probabilities, forcing one-to-one matching. Can also be used for pre- and post-processing for machine learning methods for record linkage.
- R package [RecordLinkage](https://CRAN.R-project.org/package=RecordLinkage). Implementation of the Fellegi-Sunter method for record linkage.
- R package [StatMatch](https://CRAN.r-project.org/package=StatMatch). Statistical Matching or Data Fusion
- R package [fastLink](https://cran.r-project.org/web/packages/fastLink/index.html). Implements a Fellegi-Sunter probabilistic record linkage model that allows for missing data and the inclusion of auxiliary information. Documentation can be found on http://imai.princeton.edu/research/linkage.html
- R packages [stringdist](https://CRAN.R-project.org/package=stringdist). Implements approximate string matching. Supports various string distances (Damerau-Levenshtein, Hamming, Levenshtein, optimal sting alignment), qgrams (q- gram, cosine, jaccard distance) and heuristic metrics (Jaro, Jaro-Winkler). An implementation of soundex is provided as well.
- R packages [fuzzyjoin](https://CRAN.R-project.org/package=fuzzyjoin). Join tables based on exact or similar matches. Allows for matching records based on inaccurate keys.
- R Java MySQL [RELAIS](https://joinup.ec.europa.eu/solution/relais-record-linkage-istat/releases). A toolkit providing techniques for dealing with record linkage. The purpose is to identify the same real world entity that can be differently represented in data sources. By Istat.
- R package [XBRL](https://CRAN.R-project.org/package=XBRL). Extraction of Business Financial Information from [XBRL](https://www.xbrl.org/) Documents


#### Statistical data editing and imputation  ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 5.3 | 5.4)
- R package [validate](https://CRAN.R-project.org/package=validate). Rule management and data validation.
- R package [validatedb](https://CRAN.R-project.org/package=validatedb). [validate](https://CRAN.R-project.org/package=validate) on a SQL database.
- R package [validatetools](https://CRAN.R-project.org/package=validatetools). Checking and simplifying sets of validation rules.
- R package [errorlocate](https://CRAN.R-project.org/package=errorlocate). Error localisation based on the principle of Fellegi and Holt.
    - Uses [validate](https://CRAN.R-project.org/package=validate) rule definitions
    - supports categorical and/or numeric data
    - supports linear equalities, inequalities and conditional rules.
    - Configurable backend for MIP-based error localization.
- R package [VIM](https://CRAN.R-project.org/package=VIM). Visualisation and Imputation of missing values.
    - Advanced visualisation of missing data patterns
    - Imputation using (robust) linear regression methods
    - Imputation using several donor-based methods (kNN, hot-deck)
- R package [simputation](https://CRAN.R-project.org/package=simputation). Simple imputation: many methods using a uniform interface following the [tidy tools manifesto](https://cran.r-project.org/web/packages/tidyverse/vignettes/manifesto.html)
    - Allows to easily combiny many imputation methods/strategies.
    - Supports regression (standard, M-estimation, ridge/lasso/elasticnet), hot-deck methods (powered by [VIM](https://CRAN.R-project.org/package=VIM)), randomForest, EM-based, and iterative randomForest imputation. Reuse of fitted models and definition of simple user-defined methods are supported as well.
- R package [SeleMix](https://CRAN.R-project.org/package=SeleMix). Detection of outliers and influential errors using a latent variable model for selective editing.
- R package [univOutl](https://cran.r-project.org/web/packages/univOutl/index.html). Various methods for detecting univariate outliers.
- R package [extremevalues](https://CRAN.R-project.org/package=extremevalues). Detection of univariate outliers based on modeling the bulk distribution.
- R package [deductive](https://cran.r-project.org/web/packages/deductive/index.html). Deductive correction and imputation using edit rules and (partially) complete data.
- R package [rspa](https://cran.r-project.org/web/packages/rspa/index.html). Adapt Numerical Records to Fit (in)Equality Restrictions.


#### Estimation and weighting ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 5.6 | 5.7)
- R package [survey](https://CRAN.R-project.org/package=survey). Weighting and estimation for complex survey designs, possibly under nonresponse. Also computes estimator variance. See also R package [srvyr](https:://CRAN.R-project.org/package=survey) for integration with 
[tidy tools](https://cran.r-project.org/web/packages/tidyverse/vignettes/manifesto.html).
- R package [hbsae](https://CRAN.R-project.org/package=hbsae). Small area estimation based on hierarchical Bayesian models.
- R package [rsae](https://CRAN.R-project.org/package=rsae). Small area estimation
based on (robust) maximum likelihood estimation.
- R package [CalibrateSSB](https://CRAN.R-project.org/package=CalibrateSSB). Calculate weighs and estimates for panel data with non-response.
- R package [ReGenesees](https://github.com/DiegoZardetto/ReGenesees). Has a similar interface as the R package [survey](https://CRAN.r-project.org/package=survey), along with specific features (e.g. partitioned calibration) that make it fit for processing large-scale surveys in the official statistics field. ReGenesees implements many different estimators with sampling errors, and ships with a dedicated GUI (package [ReGenesees.GUI](https://github.com/DiegoZardetto/ReGenesees.GUI)).
- R package [vardpoor](https://cran.r-project.org/package=vardpoor). Linearization of non-linear statistics and variance estimation.
- R package [convey](https://cran.r-project.org/package=convey). Variance estimation on indicators of income concentration and poverty using complex sample survey designs. Wrapper around the survey package.
- R package [icarus](https://cran.r-project.org/package=icarus). Provides detailed tools for performing calibration and several of its varitations, in a familiar setting for Calmar users in SAS.
- R package [gustave](https://cran.r-project.org/package=gustave). Provides a toolkit for analytical variance estimation in survey sampling.
- R package [rtrim](https://cran.r-project.org/package=rtrim). Trends and Indices for Monitoring data. Provides tools for estimating animal/plant populations based on site counts, including occurrence of missing data.
- R package [surveysd](https://cran.r-project.org/package=surveysd). Calibration, bootstrap and error estimation for complex surveys.
- R package [inca](https://cran.r-project.org/package=inca). Calibration weighting with integer weights.


#### Time series and seasonal adjustment ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 5.6 | 5.7)
- Fortran [X-13ARIMA-SEATS](https://www.census.gov/srd/www/x13as/) Seasonal adjustment software
produced maintained and distributed by the US Census Bureau.
- R package [seasonal](https://CRAN.R-project.org/package=seasonal). Interface to the `X13-ARIMA-SEATS` program from R with a very nice shiny GUI.
- R package [x12](https://CRAN.R-project.org/package=x12). Alternative interface to the `X13-ARIMA-SEATS` program from R with a focus on batch processing time series.
- Java application [JDemetra+](https://ec.europa.eu/eurostat/cros/content/download_en) The seasonal adjustment software officially recommended for the European Statistical System.
- R package [RJDemetra](https://jdemetra.github.io/rjdemetra/) R interface to JDemetra+.
- R package [tempdisagg](https://cran.r-project.org/package=tempdisagg) methods for temporal disaggregation and interpolation of time series.


#### Output validation ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 6.2)
- R package [validate](https://CRAN.R-project.org/package=validate). Rule management and data validation.

 
#### Statistical disclosure control ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 6.4)
- Java application [μ-ARGUS](https://github.com/sdcTools/muargus). Tool to create safe micro-data files. See also the [casc page](http://research.cbs.nl/casc/).
- Java application [T-ARGUS](https://github.com/sdcTools/tauargus). Tool to protect statistical tables. See also the [casc page](http://research.cbs.nl/casc/).
- R package [sdcMicro](https://CRAN.R-project.org/package=sdcMicro). Disclosure control for statistical microdata.
- R package [sdcTable](https://CRAN.R-project.org/package=sdcTable). Disclosure control for tabulated data.
- R package [easySdcTable](https://CRAN.R-project.org/package=easySdcTable) provides an interface to the package sdcTable.
- R package [sdcHierarchies](https://CRAN.R-project.org/package=sdcHierarchies) allows to generate, modify and export nested hierarchies.
- R package [SmallCountRounding](https://CRAN.R-project.org/package=SmallCountRounding) can be used to protect frequency tables by rounding necessary inner cells so that cross-classifications to be published are safe.
- R package [simPop](https://CRAN.R-project.org/package=simPop). Simulation of synthetic populations from census/survey data considering auxiliary information.
- R package [sdcSpatial](https://CRAN.R-project.org/package=sdcSpatial). Create privacy protected density maps from location data. Includes visual sensitivity assessment and several protection methods.
- R package [synthpop](https://CRAN.R-project.org/package=synthpop). Produce synthetic versions of microdata containing confidential information so that they are safe to be released to users for exploratory analysis.


#### Statistical Dissemination ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 7.2)
- Java application [SDMX Converter](https://ec.europa.eu/eurostat/web/sdmx-infospace/sdmx-it-tools/sdmx-converter). Converter between different versions of SDMX and formats such as CSV, FLR etc. By Eurostat.
- Java application [SDMX-RI](https://ec.europa.eu/eurostat/web/sdmx-infospace/sdmx-it-tools/sdmx-ri). Framework for disseminating data in SDMX webservices. By Eurostat.
- Node.js and other [.Stat Suite](https://sis-cc.gitlab.io/dotstatsuite-documentation/). An SDMX-based platform to build tailored data portals, topical or regional data explorers, or lightweight reporting platforms. By [SIS-CC](https://siscc.org).
- JSON [SDMX-JSON](https://github.com/sdmx-twg/sdmx-json/blob/master/data-message/docs/1-sdmx-json-field-guide.md). JSON variant of SDMX. This is still a candidate standard.
- JSON [JSON-stat](https://json-stat.org/). Lightweight JSON standard for statistical dissemination.

#### Visualisation ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 7.2)
- R package [tabplot](https://CRAN.R-project.org/package=tabplot). Compare up
  to about 10-20 variables simultaneously using a [tableplot](https://cran.r-project.org/web/packages/tabplot/vignettes/tabplot-vignette.html). See also [tabplotd3](https://CRAN.R-project.org/package=tabplot) for a
web-based GUI.
- R package [tmap](https://CRAN.R-project.org/package=tmap). Thematic geographic maps, including bubble charts, choropleths, and more.
- R package [oceanis](https://CRAN.R-project.org/package=oceanis). To create maps for statistical analysis such as proportional circles, chroropleth, typology and flows. By INSEE.
- GeoJSON/TopoJSON [cartomap](https://github.com/cartomap) A (growing) list of simplified maps useful for web cartography for World, Europe and countries.
- GeoJSON/TopoJSON [Nuts2json](https://github.com/eurostat/Nuts2json) Simplified geometries for web maps of European NUTS regions. By Eurostat.
- R package [treemap](https://CRAN.R-project.org/package=treemap). Space-filling visualisation of hierarchical data.
- R package [btb](https://CRAN.R-project.org/package=btb). Conservative kernel smoothing method for spatial analysis.
- Node.js [StatMiner](http://research.cbs.nl/Projects/StatMine/), Experimental visualization framework from Statistics Netherlands.
- JavaScript [Visual](https://github.com/idescat/visual). Javascript library for data visualization that encapsulates complexity supporting chart types such as bar, rank, pie, time series bar/line, population pyramid, scatterplots and Choropleth maps. By Idescat.
- R package [PantaRhei](https://CRAN.R-project.org/package=PantaRhei). Sankey plots suited for (circulair) economical systems such as energy systems, material flow accounts and water accounts. Supports loops. 


#### Access to official statistics ([GSBPM](https://statswiki.unece.org/display/GSBPM/) 7.4)
- R package [rsdmx](https://github.com/opensdmx/rsdmx). Easy access to data from statistical organisations that support SDMX webservices. The package contains a list of SDMX access points of various national and international statistical institutes.
- R package and C++ [readsdmx](https://cran.r-project.org/package=readsdmx). Read SDMX into dataframes from local SDMX-ML file or web-service. By OECD.
- Python [pandaSDMX](https://github.com/dr-leo/pandaSDMX). Python interface to SDMX that facilitates the acquisition and analysis of SDMX-2.1 compliant data and metadata.
- R package [rjstat](https://cran.r-project.org/package=rjstat). Read and write data sets in the JSON-stat format.
- Python package [pyjstat](https://pypi.org/project/pyjstat/). Read and write JSON-stat.
- Java module [json-stat.java](https://github.com/statisticsnorway/json-stat.java) Read and write JSON-stat. By Statistics Norway.
- R package [oecd](https://cran.r-project.org/web/packages/OECD/index.html) Search and Extract Data from the OECD
- R package [sorvi](https://CRAN.R-project.org/package=sorvi) Finnish Open Government Data Toolkit
- R package [eurostat](https://CRAN.R-project.org/package=eurostat) Tools to download data from the Eurostat database together with search and manipulation utilities.
- R package [acs](https://CRAN.R-project.org/package=acs) Download, Manipulate, and Present American Community Survey and Decennial Data from the US Census.
- R package [inegiR](https://CRAN.R-project.org/package=inegiR) Access to data published by [INEGI](http://www.inegi.org.mx/), Mexico's official statistics agency.
- R package [cbsodataR](https://CRAN.R-project.org/package=cbsodataR). Access to Statistics Netherlands' ([CBS](http://www.CBS.nl)) open data API from R.
- Node.js package [cbsodata.js](https://github.com/statmine/cbsodata.js). Access to Statistics Netherlands' ([CBS](http://www.CBS.nl)) open data API from js.
- Python package [cbsodata.py](https://github.com/J535D165/cbsodata). Access to Statistics Netherlands' ([CBS](http://www.CBS.nl)) open data API from Python.
- R package [censusapi](https://cran.r-project.org/package=censusapi) A wrapper for the U.S. Census Bureau APIs that returns data frames of Census data and metadata.
- R package [nsoApi](https://github.com/bowerth/nsoApi) builds on other packages to access data from official statistics and tries to harmonize the API.
- R package [CANSIM2R](https://CRAN.R-project.org/package=CANSIM2R). Extract CANSIM (Statistics Canada) tables and transform them into readily usable data.
- Python package [pyscbwrapper](https://github.com/kirajcg/pyscbwrapper). Access to the open data API of the Swedish Statistical Institute
- R package [pxweb](https://cran.r-project.org/package=pxweb). Generic interface for the PX-Web/PC-Axis API used by many National Statistical Agencies.
- R package [PxWebApiData](https://cran.r-project.org/package=PxWebApiData). Easy API access to e.g. Statistics Norway, Statistics Sweden and Statistics Finland.
- R package [rdbnomics](https://git.nomics.world/dbnomics/rdbnomics). Access to the [DB.nomics database](https://next.nomics.world/) which provide macroeconomic data from 38 official providers such as INSEE, Eurostat, Wolrd bank, etc.
- R package [readabs](https://cran.r-project.org/package=readabs) Download data from the Australian Bureau of Statistics.
- R package [destatiscleanr](https://github.com/cutterkom/destatiscleanr). Clean csv files from [Genesis](https://www-genesis.destatis.de/genesis/online), the database of the Federal Statistical Office of Germany (Destatis) and its regional outlets.
- R package [statcanR](https://cran.r-project.org/package=statcanR). An R connection to Statistics Canada's Web Data Service. Open economic data (formerly CANSIM tables) are accessible as a data frame in the R environment.
- R package [cdlTools](https://cran.r-project.org/package=cdlTools). Downloads USDA National Agricultural Statistics Service (NASS) cropscape data for a specified state.
- Java package [SDMX Connectors](https://github.com/amattioc/SDMX). Browse SDMX data providers, build your queries and get data directly in your favourite tool (R, SAS, Matlab, Stata and Excel). By Banca d'Italia.
- Node.js package [sdmx-rest](https://www.npmjs.com/package/sdmx-rest). This library allows to easily create and execute SDMX REST queries from a JavaScript client application.
- R package [csodata](https://cran.r-project.org/package=csodata) Download data from Central Statistics 
  Office (CSO) of Ireland.
- R package [iriR](https://cran.r-project.org/package=iriR). Client for the European Commission’s Industrial R&D Investment Scoreboard (IRI)
- R package [czso](https://cran.r-project.org/package=czso). Access open data from the Czech Statistical Office.

## Other lists
- [CSPA Service catalogue](https://www.statistical-services.org)
- [Code from NTTS 2021 publications](https://github.com/NTTSConf/NTTS21)

## Contributions

Awesome contributions are welcome, here are ways to do it:

- The GitHub way: send us a [pull request](https://help.github.com/articles/creating-a-pull-request/) to add directly to this list.
- Add an item to the
  [issue tracker](https://github.com/SNStatComp/awesome-official-statistics-software/issues)
issue tracker. (you need a GH account)
- Send an e-mail to `mark dot vanderloo at gmail dot com` or `olav dot tenbosch at gmail dot com` or tweet [\@markvdloo](https://twitter.com/markvdloo)

**Wear the badge.** Authors of software that is mentioned on this list gain the right to wear the [mentioned in awesome](https://github.com/sindresorhus/awesome/blob/master/awesome.md#awesome-mentioned-badge) badge on their website or GH repository. Please use the following code (or equivalent) to do so for your project.
```
[![Mentioned in Awesome Official Statistics ](https://awesome.re/mentioned-badge.svg)](http://www.awesomeofficialstatistics.org)
```


## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)  
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

