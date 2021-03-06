---
layout: ddc02
title: AR5 Experiments
bodyclass: ddcsim
banner: ssi/header/Header2012.html
menuclass: ar5_mon
menu: ssi12/menu1/Menu_sim_gcmm.html
links: ssi12/links/home.html
logos: ssi12/logos/dkrz.html
---
<div id="pagetitle-ln">
<h1 align="center">CMIP5 Experiments</h1>
</div>
<p>Detailed CMIP5 scenario descriptions are available at:</p>
<ul>
<li><b>Moss et al. (2008)</b>. Towards New Scenarios for Analysis of Emissions, Climate Change, Impacts, and Response Strategies. Intergovernmental Panel on Climate Change, Geneva, 132 pp. [ <a target="_blank" href="https://www.ipcc.ch/site/assets/uploads/2018/08/expert-meeting-report-scenarios.pdf">https://www.ipcc.ch/site/assets/uploads/2018/08/expert-meeting-report-scenarios.pdf</a> ]</li>
<li><b>Taylor et al. (2009/2011)</b>. A Summary of the CMIP5 Experiment Design [ <a target="_blank" href="https://pcmdi.llnl.gov/mips/cmip5/experiment_design.html">https://pcmdi.llnl.gov/mips/cmip5/experiment_design.html</a> ]</li>
<li><b>Taylor, Karl E., Ronald J. Stouffer, Gerald A. Meehl (2012)</b>. An Overview of CMIP5 and the Experiment Design. Bull. Amer. Meteor. Soc., 93, 485-498.  <a target="_blank" href="http://dx.doi.org/10.1175/BAMS-D-11-00094.1">doi:10.1175/BAMS-D-11-00094.1</a>.</li>
</ul>

<p>&nbsp;</p>
<!--<h2 align="center">Long-Term (century and longer) Scenarios</h2> -->
<h2 align="center">Long-term Projections: Centennial and longer Scenarios</h2>
<p>&nbsp;</p>
<table id="customers" width="75%" border="1" cellpadding="5" bgcolor="#f0fFf0" align="center">
<tbody>
<tr>
<th bgcolor="#c0eec0" width="5%">Exp. Number</th>
<th bgcolor="#c0eec0" width="15%">Short Name of Experiment</th>
<th bgcolor="#c0eec0" width="20%">Long Name of Experiment</th>
<th bgcolor="#c0eec0" width="60%">Experiment Description</th>
</tr>
<tr>
<td align="right">6.1</td>
<td align="left"><a id="1pctCO2">1pctCO2</a></td>
<td align="left">6.1 1 percent per year CO2</td>
<td align="left">Idealized 1% per year increase in atmospheric CO2 to quadrupling, initialized from 3.1_piControl.</td>
</tr>
<tr>
<td align="right">6.1-S</td>
<td align="left">1pctCO2</td>
<td align="left">6.1-S 1 percent per year CO2 - Shortened</td>
<td align="left">Idealized 1% per year increase in CO2 (a shortened version of expt. 6.1). initialized at year 20 of the control run (3.1-S).</td>
</tr>
<tr>
<td align="right">6.3</td>
<td align="left"><a id="abrupt4xCO2">abrupt4xCO2</a></td>
<td align="left">6.3 Abrupt 4XCO2</td>
<td align="left">Impose an instantaneous quadrupling of atmospheric CO2 (relative to preindustrial conditions) and then hold fixed.</td>
</tr>
<tr>
<td align="right">6.3-E</td>
<td align="left">abrupt4xCO2</td>
<td align="left">6.3-E Abrupt 4XCO2 - Ensemble</td>
<td align="left">Generate an ensemble of runs as in expt. 6.3, but terminated after year 5. Each ensemble member must be initialized in a different month of the year. [The initial segment of expt. 6.3 will serve as the 12th member of this ensemble.]</td>
</tr>
<tr>
<td align="right">3.3</td>
<td align="left"><a id="amip">amip</a></td>
<td align="left">3.3 AMIP</td>
<td align="left">AMIP (1979 - at least 2008). Impose SSTs and sea ice from observations, but with other conditions (including CO2 concentrations and aerosols) as in experiment 3.2_historical.</td>
</tr>
<tr>
<td align="right">3.3-E</td>
<td align="left">amip</td>
<td align="left">3.3-E AMIP Ensemble</td>
<td align="left">Additional AMIP runs (expt. 3.3) but with different initial conditions imposed on the atmosphere and possibly also the land surface. Yield an ensemble of size >=3.</td>
</tr>
<tr>
<td align="right">6.8</td>
<td align="left"><a id="amip4K">amip4K</a></td>
<td align="left">6.8 AMIP plus 4K anomaly</td>
<td align="left">Consistent with CFMIP requirements, add a uniform 4 K increase in SST to the AMIP SSTs of experiment 3.3_amip (which is the 'control' for this run).</td>
</tr>
<tr>
<td align="right">6.5</td>
<td align="left"><a id="amip4xCO2">amip4xCO2</a></td>
<td align="left">6.5 4xCO2 AMIP</td>
<td align="left">Identical to experiment 6.2b_sstClim4xCO2, but with AMIP SSTs prescribed as in experiment 3.3_amip (which is the control for this run).</td>
</tr>
<tr>
<td align="right">6.6</td>
<td align="left"><a id="amipFuture">amipFuture</a></td>
<td align="left">6.6 AMIP plus patterned anomaly</td>
<td align="left">Consistent with CFMIP requirements, add a patterned SST perturbation to the AMIP SSTs of experiment 3.3_amip (which is the 'control' for this run).</td>
</tr>
<tr>
<td align="right">6.7c</td>
<td align="left"><a id="aqua4K">aqua4K</a></td>
<td align="left">6.7c aqua planet plus 4K anomaly</td>
<td align="left">Consistent with CFMIP requirements, add a uniform 4K increase to the zonally uniform SSTs of experiment 6.7a_aquaControl (which is the control for this run).</td>
</tr>
<tr>
<td align="right">6.7b</td>
<td align="left"><a id="aqua4xCO2">aqua4xCO2</a></td>
<td align="left">6.7b 4xCO2 aqua planet</td>
<td align="left">Consistent with CFMIP requirements, impose a 4xCO2 on zonally uniform SSTs of experiment 6.7a_aquaControl (which is the control for this run).</td>
</tr>
<tr>
<td align="right">6.7a</td>
<td align="left"><a id="aquaControl">aquaControl</a></td>
<td align="left">6.7a aqua planet control</td>
<td align="left">Consistent with CFMIP requirements, impose zonally uniform SSTs on a planet without continents.</td>
</tr>
<tr>
<td align="right">5.1</td>
<td align="left"><a id="esmControl">esmControl</a></td>
<td align="left">5.1 ESM pre-industrial control</td>
<td align="left">Impose non-evolving pre-industrial conditions as in experiment 3.1_piControl but emissions-forced (with atmosperhic CO2 determined by the model itself)</td>
</tr>
<tr>
<td align="right">5.5-1</td>
<td align="left"><a id="esmFdbk1">esmFdbk1</a></td>
<td align="left">5.5-1 ESM feedback 1</td>
<td align="left">Carbon cycle sees piControl CO2 concentration, but radiation sees 1% per year rise.</td>
</tr>
<tr>
<td align="right">5.5-2</td>
<td align="left"><a id="esmFdbk2">esmFdbk2</a></td>
<td align="left">5.5-2 ESM feedback 2</td>
<td align="left">Carbon cycle sees historical/rcp45 CO2 concentration, but radiation sees 1% per year rise.</td>
</tr>
<tr>
<td align="right">5.4-1</td>
<td align="left"><a id="esmFixClim1">esmFixClim1</a></td>
<td align="left">5.4-1 ESM fixed climate 1</td>
<td align="left">Radiation code sees piControl CO2 concentration, but carbon cycle sees 1% per year rise.</td>
</tr>
<tr>
<td align="right">5.4-2</td>
<td align="left"><a id="esmFixClim2">esmFixClim2</a></td>
<td align="left">5.4-2 ESM fixed climate 2</td>
<td align="left">Radiation code sees historical/rcp45 CO2 concentration, but carbon cycle sees 1% per year rise.</td>
</tr>
<tr>
<td align="right">5.2</td>
<td align="left"><a id="esmHistorical">esmHistorical</a></td>
<td align="left">5.2 ESM historical</td>
<td align="left">Historical simulation (1850 to 2005) as in experiment 3.2_historical but emissions-forced (with atmospheric CO2 determined by the model itself)</td>
</tr>
<tr>
<td align="right">5.3</td>
<td align="left"><a id="esmrcp85">esmrcp85</a></td>
<td align="left">5.3 ESM RCP8.5</td>
<td align="left">Future projection (2006-2100) forced by RCP8.5. As in experiment 4.2_RCP8.5 but emissions-forced (with atmospheric CO2 determined by the model itself).</td>
</tr>
<tr>
<td align="right">3.2</td>
<td align="left"><a id="historical">historical</a></td>
<td align="left">3.2 Historical</td>
<td align="left">Simulation of recent past (1850 to 2005). Impose changing conditions (consistent with observations), which may include: atmospheric composition due to both anthropogenic and volcanic influences, solar forcing, emissions or concentrations of short-lived species and natural and anthropogenic aerosols or their precursors, as well as land use.</td>
</tr>
<tr>
<td align="right">3.2-E</td>
<td align="left">historical</td>
<td align="left">3.2-E Historical - Ensemble</td>
<td align="left">Historical Ensemble of 20th Century Simulations, as in experiment 3.2 but initiated from different points in experiment 3.1. Yield an ensemble of size >=3.</td>
</tr>
<tr>
<td align="right">7.4</td>
<td align="left"><a id="historicalExt">historicalExt</a></td>
<td align="left">7.4 Historical Extension</td>
<td align="left">Extend the CMIP5 historical runs to the near-present, rather than ending them in 2005. Simulations extended to at least the end of 2012 using some estimate of recent and future forcing. Groups are free to use whatever concentrations, solar forcing, SO2 emissions etc. they want to use in extending these runs. The "forcing" attribute (a netCDF global attribute) should describe what forcing is used to extend the run.</td>
</tr>
<tr>
<td align="right">7.2</td>
<td align="left"><a id="historicalGHG">historicalGHG</a></td>
<td align="left">7.2 GHG-only historical</td>
<td align="left">Historical simulation but with greenhouse gas forcing only.</td>
</tr>
<tr>
<td align="right">7.2E</td>
<td align="left">historicalGHG</td>
<td align="left">7.2E GHG-only historical - Ensemble</td>
<td align="left">Historical simulation but with green house gas forcing only - ensemble.</td>
</tr>
<tr>
<td align="right">7.3</td>
<td align="left"><a id="historicalMisc">historicalMisc</a></td>
<td align="left">7.3 historical</td>
<td align="left">Historical simulation but with other individual forcing agents, e.g. anthropogenic aerosol, or combinations of forcings. Information on the forcings used in the different model runs are summarized in the <a href="https://doi.org/10.5281/zenodo.4113081" target="_blank">CMIP5 historicalMisc forcing document</a>.</td>
</tr>
<tr>
<td align="right">7.1</td>
<td align="left"><a id="historicalNat">historicalNat</a></td>
<td align="left">7.1 natural-only historical simulation</td>
<td align="left">Historical simulation but with natural forcing only.</td>
</tr>
<tr>
<td align="right">7.1E</td>
<td align="left">historicalNat</td>
<td align="left">7.1E natural-only historical - Ensemble</td>
<td align="left">Historical simulation but with natural focing only - ensemble.</td>
</tr>
<tr>
<td align="right">3.5</td>
<td align="left"><a id="lgm">lgm</a></td>
<td align="left">3.5 Last glacial maximum</td>
<td align="left">Consistent with PMIP (Paleo Model Intercomparison Project) requirements, impose Last Glacial Maximum (21 kyrs ago) conditions including ice sheets and atmospheric concentrations of well-mixed greenhouse gasses.</td>
</tr>
<tr>
<td align="right">3.4</td>
<td align="left"><a id="midHolocene">midHolocene</a></td>
<td align="left">3.4 mid-Holocene</td>
<td align="left">Consistent with PMIP (Paleo Model Intercomparison Project) specifications, impose Mid-Holocene (6 kyrs ago) conditions including Orbital parameters and Atmospheric concentrations of well-mixed greenhouse gasses.</td>
</tr>
<tr>
<td align="right">3.6</td>
<td align="left"><a id="past1000">past1000</a></td>
<td align="left">3.6 Last millennium</td>
<td align="left">Consistent with PMIP (Paleo Model Intercomparison Project) requirements, impose evolving conditions including: Solar Variations and Volcanic Aerosols.</td>
</tr>
<tr>
<td align="right">3.1</td>
<td align="left"><a id="piControl">piControl</a></td>
<td align="left">3.1 Pre-Industrial Control</td>
<td align="left">Pre-Industrial coupled atmosphere/ocean control run. Imposes non-evolving pre-industrial conditions, which may include prescribed atmospheric concentrations or non-evolving emissions of gases, aerosols or their precursors, as well as unperturbed land use.</td>
</tr>
<tr>
<td align="right">3.1-S</td>
<td align="left">piControl</td>
<td align="left">3.1-S pre-industrial control - shortened</td>
<td align="left">Shortened version of the pre-industrial control run (experiment 3.1).</td>
</tr>
<tr>
<td align="right">4.3</td>
<td align="left"><a id="rcp26">rcp26</a></td>
<td align="left">4.3 RCP2.6</td>
<td align="left">Future projection (2006-2100) forced by RCP2.6. RCP2.6 is a representative concentration pathway, which approximately results in a radiative forcing of 2.6 W m-2 at year 2100, relative to pre-industrial conditions.</td>
</tr>
<tr>
<td align="right">4.3L</td>
<td align="left">rcp26</td>
<td align="left">4.3L RCP2.6 - Extended</td>
<td align="left">Extension of RCP2.6 through to the year 2300.</td>
</tr>
<tr>
<td align="right">4.1</td>
<td align="left"><a id="rcp45">rcp45</a></td>
<td align="left">4.1 RCP4.5</td>
<td align="left">Future projection (2006-2100) forced by RCP4.5. RCP4.5 is a representative concentration pathway, which approximately results in a radiative forcing of 4.5 W m-2 at year 2100, relative to pre-industrial conditions. RCPs are time-dependent, consistent projections of emissions and concentrations of radiatively active gases and particles.</td>
</tr>
<tr>
<td align="right">4.1L</td>
<td align="left">rcp45</td>
<td align="left">4.1L RCP4.5 - Extended</td>
<td align="left">Extension of RCP4.5 through to the year 2300.</td>
</tr>
<tr>
<td align="right">4.4</td>
<td align="left"><a id="rcp60">rcp60</a></td>
<td align="left">4.4 RCP6</td>
<td align="left">Future projection (2006-2100) forced by RCP6. RCP6 is a representative concentration pathway, which approximately results in a radiative forcing of 6 W m-2 at year 2100, relative to pre-industrial conditions.</td>
</tr>
<tr>
<td align="right">4.2</td>
<td align="left"><a id="rcp85">rcp85</a></td>
<td align="left">4.2 RCP8.5</td>
<td align="left">Future projection (2006-2100) forced by RCP8.5. RCP8.5 is a representative concentration pathway, which approximately results in a radiative forcing of 8.5 W m-2 at year 2100, relative to pre-industrial conditions. RCPs are time-dependent, consistent projections of emissions and concentrations of radiatively active gases and particles.</td>
</tr>
<tr>
<td align="right">4.2L</td>
<td align="left">rcp85</td>
<td align="left">4.2L RCP8.5 - Extended</td>
<td align="left">Extension of RCP8.5 through to the year 2300.</td>
</tr>
<tr>
<td align="right">2.1</td>
<td align="left"><a id="sst2030">sst2030</a></td>
<td align="left">2.1 2030 time-slice</td>
<td align="left">Simulation of a future decade covering the years 2026-2035, with prescribed SSTs and sea ice concentration anomalies relative to experiment 3.3_amip.</td>
</tr>
<tr>
<td align="right">2.1E</td>
<td align="left">sst2030</td>
<td align="left">2030 time-slice - Ensemble</td>
<td align="left">Additional experiment 2.1_sst2030 runs but with different initial conditions imposed on the atmosphere, sea-ice and ocean and possibly also the land). Yield an ensemble of size >=3.</td>
</tr>
<tr>
<td align="right">6.2a</td>
<td align="left"><a id="sstClim">sstClim</a></td>
<td align="left">6.2a Control SST Climatology</td>
<td align="left">AMIP-style experiment with control run climatological SSTs and sea ice.</td>
</tr>
<tr>
<td align="right">6.2b</td>
<td align="left"><a id="sstClim4xCO2">sstClim4xCO2</a></td>
<td align="left">6.2b SST Climatology With 4XCO2 Forcing</td>
<td align="left">AMIP-style experiment with control run climatological SSTs and sea ice (as in experiment 6.2a_sstClim) but with quadrupled CO2 imposed.</td>
</tr>
<tr>
<td align="right">6.4a</td>
<td align="left"><a id="sstClimAerosol">sstClimAerosol</a></td>
<td align="left">6.4a all aerosol forcing</td>
<td align="left">AMIP-style experiment with control run climatological SSTs and sea ice (as in experiment 6.2a_sstClim) but with aerosols consistent with conditions in year 2000 of the historical run (experiment 3.2)</td>
</tr>
<tr>
<td align="right">6.4b</td>
<td align="left"><a id="sstClimSulfate">sstClimSulfate</a></td>
<td align="left">6.4b sulfate aerosol forcing</td>
<td align="left">AMIP-style experiment with control run climatological SSTs and sea ice (as in experiment 6.2a_sstClim), but with aerosols consistent with conditions in year 2000 of the historical run (experiment 3.2)</td>
</tr>
</tbody>
</table>

<p>&nbsp;</p>
<!-- <h2 align="center">Near-Term (decadal) Scenarios</h2> -->
<h2 align="center">Near-term Predictions: Decadal Scenarios</h2>
<p><b>What are the Near-term Predictions?</b></p>
<p>The near-term decadal prediction experiments are initialized from observed states of the climate system to explore climate predictability and prediction on decadal to multidecadal time scales. In these simulations, the models will not only respond, as in the long-term runs, to climate forcing (e.g., increasing atmospheric CO2 concentration) but also potentially track to some degree the actual trajectory of climate change, including (within the currently unknown predictability limits of the climate system) the unforced component of climate evolution.</p>
<p>Note that decadal predictions with climate models are in an exploratory stage. A number of different methods are being tried to assimilate ocean observations into the models, and no single method has gained widespread acceptance. Moreover, the quality and completeness of ocean observations may be insufficient to realize but a fraction of the predictability inherent in the system. Thus, the forecast systems being assembled for CMIP5 are clearly not considered operational, nor will they necessarily provide more realistic simulations than the long-term simulations.</p> 

<!-- <p>Taylor, Karl E., Ronald J. Stouffer, Gerald A. Meehl (2012). An Overview of CMIP5 and the Experiment Design. Bull. Amer. Meteor. Soc., 93, 485-498.  <a target="_blank" href="http://dx.doi.org/10.1175/BAMS-D-11-00094.1">doi:10.1175/BAMS-D-11-00094.1</a>.</p> -->

<table id="customers2" width="75%" border="1" cellpadding="5" bgcolor="#f0fFf0" align="center">
<tbody>
<tr>
<th bgcolor="#c0eec0" width="5%">Exp. Number</th>
<th bgcolor="#c0eec0" width="10%">Short Name of Experiment</th>
<th bgcolor="#c0eec0" width="25%">Long Name of Experiment</th>
<th bgcolor="#c0eec0" width="60%">Experiment Description</th>
</tr>
<tr>
<td align="right">1.5</td>
<td align="left"><a id="decadal">decadalXXXX</a></td>
<td align="left">1.5 decadal hindcast/prediction utilizing alternative initializations.</td>
<td align="left">Decadal hindcast/prediction. Comparison of initialization strategies - for example, a repeat of experiment 1.1_decadal1960 using an alternate initialization strategy or alternate initial data. 'XXXX' indicates the start year.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1960">decadal1960</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1960</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1960</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1960 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1960) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.2</td>
<td align="left">decadal1960</td>
<td align="left">1.2 30-year prediction/hindcast initialized in year 1960</td>
<td align="left">Extend to 30 years the experiment 1.1 integration with initial date in 1960. A minimum ensemble size of 3 should be produced.</td>
</tr>
<tr>
<td align="right">1.2-E</td>
<td align="left">decadal1960</td>
<td align="left">1.2-E 30-year hindcast/prediction initialized in year 1960 - O(10)</td>
<td align="left">Additional runs for experiment 1.2 (1960) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1965">decadal1965</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1965</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1965</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1965 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1965) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1970">decadal1970</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1970</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1970</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1970 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1970) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1975">decadal1975</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1975</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1975</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1975 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1975) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1980">decadal1980</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1980</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1980</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1980 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1980) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.2</td>
<td align="left">decadal1980</td>
<td align="left">1.2 30-year prediction/hindcast initialized in year 1980</td>
<td align="left">Extend to 30 years the experiment 1.1 integration with initial date in 1980. A minimum ensemble size of 3 should be produced.</td>
</tr>
<tr>
<td align="right">1.2-E</td>
<td align="left">decadal1980</td>
<td align="left">1.2-E 30-year hindcast/prediction initialized in year 1980 - O(10)</td>
<td align="left">Additional runs for experiment 1.2 (1980) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1985">decadal1985</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1985</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1985</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1985 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1985) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1990">decadal1990</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1990</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1990</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1990 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1990) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal1995">decadal1995</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 1995</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal1995</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 1995 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (1995) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2000">decadal2000</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2000</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal2000</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 2000 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (2000) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2001">decadal2001</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2001</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2001</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2001 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2001 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2002">decadal2002</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2002</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2002</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2002 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2002 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2003">decadal2003</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2003</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2003</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2003 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2003 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2004">decadal2004</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2004</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2004</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2004 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2004 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2005">decadal2005</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2005</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-E</td>
<td align="left">decadal2005</td>
<td align="left">1.1-E 10-year hindcast/prediction initialized in year 2005 - O(10)</td>
<td align="left">Additional runs for experiment 1.1 (2005) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2005</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2005 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2005 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.2</td>
<td align="left">decadal2005</td>
<td align="left">1.2 30-year prediction/hindcast initialized in year 2005</td>
<td align="left">Extend to 30 years the experiment 1.1 integration with initial date in 2005. A minimum ensemble size of 3 should be produced.</td>
</tr>
<tr>
<td align="right">1.2-E</td>
<td align="left">decadal2005</td>
<td align="left">1.2-E 30-year hindcast/prediction initialized in year 2005 - O(10)</td>
<td align="left">Additional runs for experiment 1.2 (2005) to expand ensemble to a size of O(10).</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2006">decadal2006</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2006</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2006</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2006 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2006 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2007">decadal2007</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2007</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2007</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2007 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2007 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2008">decadal2008</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2008</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2008</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2008 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2008 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2009">decadal2009</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2009</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.1-I</td>
<td align="left">decadal2009</td>
<td align="left">1.1-I 10-year hindcast/prediction initialized in year 2009 - additional start dates</td>
<td align="left">As in experiments 1.1 and 1.1-E, but initialized near the end of 2009 to take advantage of the better ocean data of the Argo float era.</td>
</tr>
<tr>
<td align="right">1.1</td>
<td align="left"><a id="decadal2010">decadal2010</a></td>
<td align="left">1.1 10-year hindcast/prediction initialized in year 2010</td>
<td align="left">The atmospheric composition (and other conditions) should be prescribed as in the historical run (expt. 3.2) and the RCP4.5 scenario (expt. 4.1) of the long-term suite of experiments. Ocean initial conditions should be in some way representative of the observed anomalies or full fields for the start date. Land, sea-ice and atmosphere initial conditions are left to the discretion of each group.</td>
</tr>
<tr>
<td align="right">1.3</td>
<td align="left"><a id="noVolc1960">noVolc1960</a></td>
<td align="left">1.3 hindcast without volcanoes </td>
<td align="left">Hindcast without volcanoes. Additional 10-year run for experiment 1.1 from 1960 without including the Agung, El Chichon and Pinatubo eruptions.</td>
</tr>
<tr>
<td align="right">1.3</td>
<td align="left"><a id="noVolc1975">noVolc1975</a></td>
<td align="left">1.3 hindcast without volcanoes </td>
<td align="left">Hindcast without volcanoes. Additional 10yr run for experiment 1.1 from 1975 without including the Agung, El Chichon and Pinatubo eruptions.</td>
</tr>
<tr>
<td align="right">1.3</td>
<td align="left"><a id="noVolc1980">noVolc1980</a></td>
<td align="left">1.3 hindcast without volcanoes </td>
<td align="left">Hindcast without volcanoes. Additional 10yr run for experiment 1.1 from 1980 without including the Agung, El Chichon and Pinatubo eruptions.</td>
</tr>
<tr>
<td align="right">1.3</td>
<td align="left"><a id="noVolc1985">noVolc1985</a></td>
<td align="left">1.3 hindcast without volcanoes </td>
<td align="left">Hindcast without volcanoes. Additional 10yr run for experiment 1.1 from 1985 without including the Agung, El Chichon and Pinatubo eruptions.</td>
</tr>
<tr>
<td align="right">1.3</td>
<td align="left"><a id="noVolc1990">noVolc1990</a></td>
<td align="left">1.3 hindcast without volcanoes </td>
<td align="left">Hindcast without volcanoes. Additional 10yr run for experiment 1.1 from 1990 without including the Agung, El Chichon and Pinatubo eruptions.</td>
</tr>
<tr>
<td align="right">1.4</td>
<td align="left"><a id="volcIn2010">volcIn2010</a></td>
<td align="left">1.4 decadal prediction with 2010 volcano</td>
<td align="left">Pinatubo-like eruption imposed. Repeat of the experiment 1.1_decadal2005 forecast with an imposed 'Pinatubo' eruption in 2010.</td>
</tr>
</tbody>
</table>

<p>&nbsp;</p>

<p align="center">&nbsp;</p>
<p align="left">
<i>Source: CMIP5 Questionnaire (http://q.cmip5.ceda.ac.uk/feeds/cmip5/experiment/; last access: 2014-01-08)<br />
Contact: dataATdkrz.de</i></p>


