# COVID-19: State Responses and Their Impact
## Knowledge Discovery in Databases Final Project
 
<h3>Team Members:</h3> 
<ul>
<li>Hari Chamlagai | https://github.com/chamlagaig</li>
<li>James Mason | https://github.com/jkpm18</li>
<li>Soumyadip Mitra | https://github.com/soumyadipmitra</li>
<li>Phil Nguyen | https://github.com/gong-boy</li>
<li>Ramya Prakash | https://github.com/RamyaPrakashPT</li>
</ul>

<h3>Professor:</h3>
<ul>
<li>Dr. Pamela Thompson | http://www.profthompson.net/ </li>
</ul>

<h3>Project Introduction</h3>
	<p>It has been several months since the COVID-19 pandemic began its rapid spread across the globe. There has been high variability in the types of responses taken by local and national leadership around the world in attempts to react to the virus with differing degrees of success. For this project we narrow our focus to the situation in the United States as we investigate the effect of the political parties of State Governors.</p>
	<p>On January 11, 2020, China announced its first novel coronavirus death, and on January 21 the United States declared its first confirmed case. By March 26 the United States had the most confirmed cases in the world. Thus, it is a worthwhile endeavour to explore some of the factors involved in the growth of the virus in the U.S. We use regression analysis to determine what relationships exist, if any, between two different dependent variables (state incident rate and state death rate) and a number of state-level features including state governor’s political party, governor’s sex, governor’s age at the date of the first confirmed U.S. case, governor’s time in office at the date of first U.S. case, state’s stay-at-home order response time, testing rate, population density, median household income, state GDP, and the percent of population that is in the high-risk age group (65+).</p>


<h3>Research Question</h3>
<p>What is the impact of the State Governor’s Political Party in addressing Covid-19 pandemic?</p>


<h3>Relevant Domain Information</h3>
<ol>
<li>CDC Weekly Surveillance Summary of U.S. COVID-19 Activity (https://www.cdc.gov/coronavirus/2019-ncov/covid-data/covidview/index.html?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fcoronavirus%2F2019-ncov%2Fcovid-data%2Fcovidview.html)</li>
<li>COVID-19 data processing with Pandas DataFrame (https://towardsdatascience.com/covid-19-data-processing-58aaa3663f6)</li>
<li>COVID-19 Timeline (https://abcnews.go.com/Health/timeline-coronavirus-started/story?id=69435165)</li>	
</ol>

<h3>Data Sources</h3>
<ol>
<li>COVID-19 Data Repository by CSSE at Johns Hopkins (https://github.com/CSSEGISandData/COVID-19)</li>
<li>U.S. Governors by Age: to obtain DOB & Inauguration Date (https://en.wikipedia.org/wiki/List_of_current_United_States_governors_by_age)</li>
<li>U.S. Governors Data: to obtain sex & political party  (https://en.wikipedia.org/wiki/List_of_United_States_governors)</li>
<li>Stay-At-Home Order Dates (https://www.kff.org/coronavirus-policy-watch/stay-at-home-orders-to-fight-covid19/)</li>	
<li>School Closures Data Set (https://www.edweek.org/ew/section/multimedia/map-coronavirus-and-school-closures.html)</li>
<li>Policy Actions Data Set (https://www.kff.org/coronavirus-covid-19/issue-brief/state-data-and-policy-actions-to-address-coronavirus/)</li>
<li> Bureau of Economic Analysis: State GDP (https://www.bea.gov/news/2020/gross-domestic-product-state-1st-quarter-2020)</li>	
<li>U.S. Census State Populations (https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html)</li>
<li>U.S. Census State Area Measurements (https://www.census.gov/geographies/reference-files/2010/geo/state-area.html)</li>
<li>Median Household Income by State (https://www.kff.org/other/state-indicator/median-annual-income/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D)</li>	
<li>Population Distribution by Age Group (https://www.kff.org/other/state-indicator/distribution-by-age/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D)</li>
</ol>


<h3>Approach:</h3>
<ol>
<li><b>Data understanding and EDA</b></li>
<li><b>Date Preparation:</b>
We combined several publicly-available data sets.</li>  
<li><b>Machine Learning (if applicable - supervised, unsupervised):</b>
We plan to develop predictive models that will use the party affiliation of a state’s governor as well as certain closure decisions to predict current hospitalization rate, deaths/million and cases/million. We intend to control for factors such as state GDP, household income, population, and large city count.</li>
<li><b>Evaluation:</b></li>  	  	
</ol>

<h3>Known Issues (problems with predictors, reporting, bias, etc.)</h3>
<p>One significant issue might be that there is not necessarily uniformity in how states report testing, deaths, hospitalizations, and confirmed cases. So this must be kept in mind when comparing numbers between the states. Another issue is sample size. When building a model using predictor variables to model the Incident Rate and Death Rate per state, the data by definition will only have 50 observations (one observation for each state). So the size of the data set for such an analysis is not as large as most “big data” data sets. </p>
 
<h3>Conclusion</h3>
<p>This is where the conclusion will go</p>
