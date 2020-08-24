Energy Data Sources
===================

This repository contains links to up-to-date Ireland energy usage data sources 

Have a new data source to add? Great! Please follow the `how-to` guide below and submit it.

Found a broken data source URL? Excellent! Please follow the `how-to` guide below and submit it fixed or removed.

Would rather solve the issue via email? No problem, email us at `codema-dev@codema.ie`

---

Table of Contents
=================

<!--ts-->
   * [Energy Data Sources](#energy-data-sources)
   * [Table of Contents](#table-of-contents)
   * [How to Contribute?](#how-to-contribute)
   * [Energy Usage Data](#energy-usage-data)
   * [Building Fabric Data](#building-fabric-data)
   * [Geodata](#geodata)
   * [Benchmarks](#benchmarks)
<!--te-->

---

How to contribute?
==================

If you find a data source that is missing from the list, please edit the ReadMe file and submit a pull request. 

Here’s a quick guide to editing GitHub Markdown files on GitHub, if you’re new to this:

- Click the pencil icon in the top-right corner and make changes ([here’s a lovely Markdown tutorial](https://commonmark.org/help/tutorial/) if you need it). 
- Make your changes
- Scroll down to `Commit Changes`, summarise the changes & add a quick explanation on why the change should be made.
- Click `Create a new branch for this commit and start a pull request.` and rename `patch-1` with a dash-separated summary
- Click `Propose Changes`
- Click `Create pull request`. Thank you! 🎉

> Adapted from [`list-of-python-api-wrappers`](https://github.com/discdiver/list-of-python-api-wrappers/blob/master/readme.md) and this excellent [Medium.com article](https://towardsdatascience.com/how-to-get-data-from-apis-with-python-dfb83fdc5b5b)

---

Energy Usage Data
=================

Commission for Regulation of Utilities (CRU) Smart Meter Trials Data
--------------------------------------------------------------------
- Electricity meter data at 15-minute resolution for a sample of 5,000 Irish homes and businesses between 2009-10
- Gas meter data at 15-minute resolution for a representative sample of nearly 2,000 Irish homes between 2010-11
- https://www.ucd.ie/issda/data/commissionforenergyregulationcer/

Gas Network's Ireland Networked Gas Consumption data
----------------------------------------------------
- Annual Gas consumption data for all Irish Power Plants, Residential & Non-Residential
- https://www.cso.ie/en/statistics/climateandenergy/networkedgasconsumption/

Environmental Protection Agency (EPA) Annual Energy Use Data
------------------------------------------------------------
- Annual Gas & Electricity data for Emissions Trading System (ETS) industrial buildings 
- http://epa.ie/licensing/

---

Building Fabric Data
====================

SEAI's 2016 Census Small Area Data
----------------------------------
- Building data (period built, dwelling type ...) for all households in Ireland who participated in the 2016 Census at areas of population generally comprising between 80 and 120 dwellings.
- https://www.cso.ie/en/census/census2016reports/census2016smallareapopulationstatistics/

SEAI's BER Public Search Data
---------------------------------
- Building data (type of heating, building geometry ...) for all households in Ireland who have had their household's BER rating evaluated.
- Updated nightly
- https://ndber.seai.ie/BERResearchTool/Register/Register.aspx

Valuation Office Data
-------------------------
- Building data (floor areas ...) for all Commercial buildings in Ireland
- __Note:__ Can apply benchmarks to these floor areas to estimate commercial building energy usage
- https://opendata.valoff.ie/api/

---

Geodata
=======

SEAI's 2016 Census Small Area Geometries 
--------------------------------------------
Contains mappable geometries for all Small Areas.
- https://www.cso.ie/en/census/census2016reports/census2016smallareapopulationstatistics/

Shane McGuinness' (of Trinity College) Dublin Postcodes Geometries
------------------------------------------------------------------
Contains mappable geometries for all Dublin Postcodes.
 - https://github.com/rdmolony/dublin-postcode-shapefiles) 


---

Benchmarks
==========

Chartered Institute of Building Services Engineers (CIBSE) 2008
---------------------------------------------------------------
- Commercial sector building fossil fuel and electricity benchmarks by building type
- https://www.metrocommercial.co.uk/images/resources/CIBSE_TM46_Energy%20Benchmarks.pdf
