# awesome-safegraph-datascience

This site is a community, crowdsourced collection of code, tools, datasets, and other resources related to 
SafeGraph Data and the [SafeGraph Data consortium](https://www.safegraph.com/covid-19-data-consortium). Thousands of organizations work with SafeGraph Data, and are contributing to COVID-19 data science research through the [Safegraph Data Consortium](https://github.com/SafeGraphInc/awesome-safegraph-datascience#safegraph-data-consortium). We are leveraging the [awesome-list] approach to organize and share the rapidly growing set of contributions from this community.

**Please add to the list** :thumbsup: :chart_with_upwards_trend: **:**

Do you have a software tool, research project, use case, code snippet, or data product related to or using SafeGraph data, that you'd like to recommend or share? Please add it to the list using either:

1) a [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) with your items added to the list. This is so easy, you can [just edit the file directly in your browser](https://github.com/SafeGraphInc/awesome-safegraph-datascience/edit/master/README.md) and then click the "commit" button. 
or 
2) an [new issue](https://github.com/SafeGraphInc/awesome-safegraph-datascience/issues/new/choose) that includes details of what to add (link, description) and we will add it. 

Don't see a category that matches your needs--make a new one! 

You can find out more about awesome-lists [HERE](https://github.com/sindresorhus/awesome/blob/main/contributing.md)

If you would like to know about different methods in which to add to the awesome-list, please checkout this [step-by-step guide](https://docs.google.com/document/d/1QEQig2jo79D0pFio7D4LbMwwoKhytucScNtZXnUA4SU/edit?usp=sharing) 

## What is SafeGraph?

[SafeGraph](https://www.safegraph.com/) is a geospatial data company. "Unlock innovation with the most accurate Points-of-Interest (POI) data, business listings, & store visitor insights data for commercial places in the U.S." Here is a full list of [SafeGraph data sets](https://docs.safegraph.com/docs/places-schema) which you can search in the [SafeGraph Data Bar](https://shop.safegraph.com/) (use coupon `AwesomeDataScience` for $100 free data).

----------
## Code
A list of code snippets, scripts, notebooks, and workflows for reproducing awesome data science with SafeGraph data

### python 
* [SafeGraph Core Places Starter Notebook -- CoLab](https://colab.research.google.com/drive/1OUopjpogmucEghS_7Ufxl3lKIp8s9H1h#offline=true&sandboxMode=true) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph) -- Brand new to SafeGraph Places data? This will help you get oriented. 
* [Simple Outlier Filtering -- CoLab Notebook](https://colab.research.google.com/drive/1LwQNJp9qI0abUzd5jYwT_xJTHJ98iZsD#sandboxMode=true) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph) -- Python Google CoLab Notebook showing simple IQR\*k based outlier filtering
* [Quickly visualize SafeGraph data on a map with python -- CoLab Notebook](https://colab.research.google.com/drive/1_0KvKUMYP1mf6ZAhM0X4LTDUPHzsz40e#offline=true&sandboxMode=true) from [Ryan Fox Squire](https://github.com/ryanfoxsquire)
* [Accessing JSON objects inside of Pandas](https://colab.research.google.com/drive/1Bcx-JI2qfUbRPJ4N9NhwpgASRZsSVxPp?usp=sharing) from [Jack Lindsay](https://github.com/Trippl7777/code_repo) Python Google Co-Lab Notebook showing how to explode JSON objects into multiple columns
*	[Connecting Safegraph_place_id to Census Block Groups (CBGs) -- CoLab notebook](https://colab.research.google.com/drive/1Kt3vPVIQJUq4QeJ-rE08URpIJEr1g2H3#offline=true&sandboxMode=true) by [Ryan Fox Squire](https://github.com/ryanfoxsquire)
* [Download from Wasabi with Boto3](https://github.com/SafeGraphInc/safegraph_py/blob/master/Boto3_template.py) from Thomas Roderick
* [Demo for getting started with SafeGraph Open Census Data Google CoLab Notebook](https://colab.research.google.com/drive/1JgU2MPUrITJBiEynZnFrZ8JyZAFYZY_1#offline=true&sandboxMode=true) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Python Library for wrangling Open Census Data for Demographic Analysis](https://github.com/ryanfoxsquire/safegraph_demo_profile) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Databricks Python Notebook: Simple Demo of Analyzing Starbucks visitors from SafeGraph Patterns](https://kona-demo-s3.s3.us-east-2.amazonaws.com/databricks-safegraph-aws-junto/Safegraph-Starbucks-Demo.html) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Calulate area / square footage from SafeGraph Geometry polygon_wkt using geopandas](https://colab.research.google.com/drive/1gnImutSovH9zBr1yuazfsy4DfIGm3dr9#forceEdit=true&sandboxMode=true&scrollTo=soL6rZLeJlpw) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Demo for getting started with Monthly Patterns Data in Jupyter Notebook with SQLite](https://github.com/SafeGraphInc/safegraph_py/blob/master/monthly-patterns-demo-SQLite.ipynb) from [Ryan Kruse](https://github.com/kruser1)
* [Demo for getting started with Social Distancing Data in Jupyter Notebook with SQLite](https://github.com/SafeGraphInc/safegraph_py/blob/master/social-distancing-demo-SQLite.ipynb) from [Ryan Kruse](https://github.com/kruser1)
* [Matching CBGs to ZCTAS (Zip code tabulation areas) using geopandas for Covid-19 research](https://github.com/graziul/covid19/blob/master/COVID-19%20CBG%20to%20ZCTA.ipynb) from [Chris Graziul](https://github.com/graziul/) (University of Chicago)
* [Unfolded SQL-Query Helper for directly querying Unfolded in Python](https://github.com/bpblakely/unfolded-sql-helper) from [Brian Blakely](https://github.com/bpblakely) (Bowling Green State University)
* [Merging patterns with core_places](https://colab.research.google.com/drive/1OscKxe9rvNNiiyN6iJ_pb0-Ubeeln2tZ?usp=sharing) from [Jack Lindsay](https://github.com/Trippl7777/code_repo) - a short notebook displaying how you can merge the weekly patterns to the core places data
* [CBG to zipcode/ZCTA merge](https://colab.research.google.com/drive/15674RPOwzPFA961qs3hn-HY1XqwjuQPK?usp=sharing) - A notebook showing how to make a master dataset that includes a cross reference for nearly all CBG to ZCTA to Zipcode conversion
* [Automated Download and Filtering, Prep for Normalization (Monthly Patterns)](https://colab.research.google.com/drive/1osFqVNDNZX1RngQPCd2ntG0qxQmxF4zY?usp=sharing) - A notebook to easily filter monthly patterns to your desired POIs, and prepare data for use with [SafeGraph's normalization best practices](https://colab.research.google.com/drive/16BELpcum4TKoH-5wg8Xym_CGgIGgpu1I?usp=sharing), allowing you to start analyzing more quickly from [Ryan Kruse](https://github.com/kruser1)


### R
* The [SafeGraphR github repo](https://github.com/SafeGraphInc/SafeGraphR) -- Package for reading and analyzing SafeGraph foot traffic data
* [The Stanford Future Bay Initiative: Covid-19 Rapid Response Projects](https://github.com/stanfordfuturebay/stanfordfuturebay.github.io/tree/master/covid19) -- a collection of R functions and documentation for processing, normalizing, and analyzing SafeGraph foot-traffic data
* A [Demonstration](https://nickch-k.github.io/SafeGraphRProcessing/County_Level_Distancing_Demonstration.html) of how to do population weighting and Hierarchical Bayes shrinkage with SafeGraph social distancing data.
* For SafeGraph social distancing metrics, [map census tracts to zip codes](https://github.com/jwilliamsholt/safegraph-in-r/blob/master/social_distance_by_tract_and_by_zip.rmd). 
* [Spatial crosswalks](https://github.com/jwilliamsholt/safegraph-in-r/blob/master/spatial-crosswalks.Rmd). Includes CBGs to ZCTAs, census tracts to zip codes, and zip codes to ZCTAs.
* [Sample Raster Codes](https://github.com/kschertz/RasterCodes); getting raster statistics at census tract or county level.

#### Basic R fuctions.
* [Sync SafeGraph data](https://github.com/jwilliamsholt/safegraph-in-r/blob/master/sync-safegraph-endpoint.Rmd) to a local directory using the `aws.s3` package.

### Excel / Spreadsheets
* Awesome examples of SafeGraph data analysis with spreadsheets

### STATA
* Awesome examples of SafeGraph data analysis with STATA


----------
## Analysis Frameworks
* [Best Practices For Correlating SafeGraph Patterns With Other Datasets Across Time](https://colab.research.google.com/drive/16BELpcum4TKoH-5wg8Xym_CGgIGgpu1I?usp=sharing) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph) 
* [Macro and Micro approaches to estimating true counts from SafeGraph data](https://docs.google.com/presentation/d/1a7lmVtulPpvuH-TPgsR_t5WUQPdT28c_ymyx_Bcankk/edit#slide=id.g86ef4ba4cf_0_922) from [Derek Ouyang](https://github.com/derekouyang) ([Stanford Future Bay Initiatve](https://github.com/stanfordfuturebay/stanfordfuturebay.github.io/tree/master/covid19))
* [Memo](https://docs.google.com/document/d/1EBnvd_CHKJ1Tzsvi364xK13YAg3tH2BTscHQ7JrPgxg/edit?usp=sharing) and [Spreadsheet Example](https://docs.google.com/spreadsheets/d/1A0KLTyRzx2DrYbagyi4_W4bKmgHqIsKGnq4O4W-tGy4/edit?usp=sharing) for Simple Example of "Micro" CBG-based Normalization to estimate "True Visits" by day --  from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Details on The Covid19 Commerce Patterns Dashboard from SafeGraph](https://docs.google.com/document/d/1lWodAzENz6rMlcFdPi6Y_B4M_ruCyXgeYoC8k9yY2eI/edit?usp=sharing) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Data Analysis Methodology for the SafeGraph Stay-At-Home Index](https://docs.google.com/document/d/1k_9LGQn95P5gHsSeuBdzgtEWGGCmzXdcOkcphWi0Cas/edit?usp=sharing) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [SafeGraph's Shelter-in-place index Appendix: Bayesian Hierarchical Models and Empirical Bayes](https://docs.google.com/document/d/1qAXl5iHJZCuyIPnawMHa6WoKULhsx404flTAGq0bStA/edit#heading=h.k77dnm4cnt3l) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Measuring and Correcting Sampling Bias in Safegraph Patterns for More Accurate Demographic Analysis](https://www.safegraph.com/blog/measuring-and-correcting-sampling-bias-for-accurate-demographic-analysis) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Analyze Demographic Profiles of Retail Visitors From SafeGraph Patterns Data](https://blog.safegraph.com/safegraphs-data-on-brick-and-mortar-customer-demographics-is-the-most-accurate-and-comprehensive-86915c507c20) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [Calculate Statistics and Confidence Intervals from SafeGraph Patterns](https://blog.safegraph.com/demographic-profiles-with-rigorous-statistics-using-safegraph-patterns-data-9836b9d02310) from [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* [SafeGraph's Visit Attribution Whitepaper](https://www.safegraph.com/visit-attribution) -- How does SafeGraph combine GPS data and point-of-interest polygon data to measure visits. 
* [Covid-19 Case Count Forecasting using SafeGraph data](https://github.com/UT-Covid/USmortality/blob/6058aec5333f9990ff0dfd47f74b85f6d7a9f073/README.md#what-data-sources-do-you-use) from UT Austin
8 [A weekly fatality counts prediction model ](https://github.com/kpelechrinis/epiDAMIK20-COVID/blob/master/prediction/COVID19-prediction.ipynb) from [Kostas Pelechrinis](https://github.com/kpelechrinis)

----------
## Results, Dashboards, and Visualizations (Inspiration)
* [SafeGraph Data Publications](https://www.safegraph.com/publications) -- Full list of all publications using SafeGraph data. If you see something is missing, please let SafeGraph know by emailing datastories AT safegraph DOT com
* [The SafeGraph Covid-19 Re-opening Dashboard](https://www.safegraph.com/dashboard/reopening-the-economy-foot-traffic) -- built with plot.ly and Dash
* [SafeGraph Weekly Patterns Disaster Response Map](https://disasterresponse.maps.arcgis.com/apps/InteractiveLegend/index.html?appid=73fd8d40039c4df2a0e0644c35ab75e9) from Esri -- built with Arcgis Online
* [Social Distancing Compliance Dashboard for City of San Jose](https://stanfordfuturebay.shinyapps.io/sanjose/) from [Stanford Future Bay](http://bay.stanford.edu/covid19)using R Shiny 
* [Covid-19 Cases and Point-of-interest Visit correlation dashboard](https://stanfordfuturebay.shinyapps.io/cases_visits_dashboard/) from [Stanford Future Bay](http://bay.stanford.edu/covid19) using R Shiny 
* [UT Austin Covid-19 Forecasting using SafeGraph data](https://covid-19.tacc.utexas.edu/projections/) 

----------
## Helpful Free Software / Websites 
* [SafeGraph Free Point-of-interest Matching Tool](https://docs.safegraph.com/docs/matching-service-overview)
* [How to Join X with Y](https://docs.google.com/spreadsheets/d/14xMfW9xAXZLWuNcrSzxL16ddve0HAQ21zh99RAOjpsM/edit?usp=sharing) a collection of free resources/tools for joining different geospatial areas together (e.g., County <> Zip Code)
* [SafeGraph USA census block group lookup and visualization](http://safegraph.maps.arcgis.com/apps/webappviewer/index.html?id=d2a747428fd74ba6ae80ca6d677672bd) -- want to quickly see the shape of a CBG on a map? 
* [Movable-type Geohashes page](https://www.movable-type.co.uk/scripts/geohash.html)
* [arthur-e polygon WKT visualization](https://arthur-e.github.io/Wicket/sandbox-gmaps3.html)
* [Google CoLab](https://colab.research.google.com/notebooks/intro.ipynb) -- FREE cloud-hosted python notebooks 


----------
## Recommended Licensed Software Tools
* Esri
  * [SafeGraph Data freely available on Esri Marketplace](https://marketplace.arcgis.com/listing.html?id=3425348e4bee4059af2b353e52df43c2)
* CARTO
  * [SafeGraph and CARTO co-hosted Demo Webinar](https://www.youtube.com/watch?v=-bo24qhQwmY&feature=youtu.be&t=1)
* Databricks
  * [Databricks Python Notebook: Simple Demo of Analyzing Starbucks visitors from SafeGraph Patterns](https://kona-demo-s3.s3.us-east-2.amazonaws.com/databricks-safegraph-aws-junto/Safegraph-Starbucks-Demo.html) by [Ryan Fox Squire](https://github.com/ryanfoxsquire) (SafeGraph)
* Snowflake
  * [SafeGraph data available in Snowflake](https://www.snowflake.com/datasets/safegraph/)
* Tableau
* PowerBI


----------
## SafeGraph Documentation
* [SafeGraph Docs page](https://docs.safegraph.com/docs)
* [SafeGraph data science resources page](https://docs.safegraph.com/docs/data-science-resources) - Lots of notebooks and demos using SafeGraph data produced by SafeGraph
* [SafeGraph FAQ](https://docs.safegraph.com/docs/faqs)
* [SafeGraph Places Manual](https://docs.safegraph.com/docs/places-manual)
* [SafeGraph Monthly Release Notes](https://docs.safegraph.com/changelog)


----------
## SafeGraph Data Consortium
* The coronavirus (COVID-19) global pandemic has brought massive and ongoing changes, including to how people interact with their surroundings and participate in the economy. SafeGraph is providing free access to various datasets to help researchers, non-profits, and governments around the world respond to COVID-19 (Coronavirus).
* [Sign-up to join the Data Consortium](https://www.safegraph.com/covid-19-data-consortium)
* [SafeGraph Data Consortium Quick Start Guide](https://docs.google.com/document/d/1Xx-nzOX1qF3WfOpg4D8aemwFrrAkQaJuT0-1-CbgxQs/edit?usp=sharing)
* [SafeGraph Data Consosrtium Products Spreadsheet](https://docs.google.com/spreadsheets/d/1UNWvPzkUTTlXBZ6M6iGhM_7sr8h-MxsZdE7iOszkAmk/edit#gid=0)
* [Data Consortium FAQ](https://docs.google.com/document/d/1h-pkpIZWeynF3_BcylRmgeWS7282kIUGoM0TSSIUhgM/edit?usp=sharing)




