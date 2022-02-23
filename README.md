# COVID Testing and Vaccines and Health Equity 

## Question
* What is the question behind your analysis or model and what practical impact will your work have?<br/>
    * How might we address COVID testing and vaccine health equity for people who commute after 7 pm and before 7 am, by sending mobile testing and vaccine units near subway stations in zip codes most affected by COVID?<br/>
    * Providing COVID monitoring and prevention services during off-hours would impact New Yorkers during their commute, despite irregular work hours. Furthermore, it would impact New York City's response to COVID surges by providing services to people who they may otherwise not easily reach.<br/> 
* Who is your client and how will that client benefit from exploring this question or building this model/system?<br/>
    * Client: [New York City Department of Health and Mental Hygience](https://www1.nyc.gov/site/doh/about/about-doh.page)<br/>
    * The NYC Department of Health would benefit by knowing where to allocate COVID testing and vaccine mobile units during late-night and early-morning hours. Serving people in NY who cannot access COVID services during normal business hours helps mitigate surges of COVID. Serving this population would also address health equity issues for shift workers who are often also low-wage workers and have limited access to healthcare.<br/>     
    
## Data Description
* What dataset(s) do you plan to use, and how will you obtain the data? <br/>
    * [NYC Coronovirus Data by Zip Code](https://github.com/nychealth/coronavirus-data/blob/master/totals/data-by-modzcta.csv)<br/>
    * [NYT Coronavirus by Zip Code](https://www.nytimes.com/interactive/2020/nyregion/new-york-city-coronavirus-cases.html)<br/>
    * [HealthNY Test Site Finder](https://coronavirus.health.ny.gov/find-test-site-near-you)<br/>
    * [NYC Demographic Statistics By Zip CodeCity](https://data.cityofnewyork.us/City-Government/Demographic-Statistics-By-Zip-Code/kku6-nxdu)<br/>
    * [NYC Disparity Report Update 2021](https://www1.nyc.gov/assets/cidi/downloads/pdfs/2021-disparity-report-update.pdf)<br/>
    * [Health Disparities in New York City](https://www.commonwealthfund.org/sites/default/files/documents/___media_files_publications_other_2004_jul_health_disparities_in_new_york_city_karpati_disparities_pdf.pdf)<br/>
* What is an indivudal sample/unit of analysis in this project?<br/>
    * An individual sample in one row, which is also one data point.<br/> 
* What charactersics/features do you expect to work with?<br/>
    * Features of interest are date, time, station, linename, entry and exit.<br/>

## Tools
* How do you intend to meet the tools requirement of the project?<br/>
    * SQL, Matplotlib, Seaborn <br/>
* Are you planning in advance to need or use additional tools beyond those required?<br/>
    * None at this time.<br/>

## MVP Goal
* What would a [minimum viable product (MVP)](https://app.thisismetis.com/courses/135/pages/minimum-viable-product-mvp-template) look like for this project?<br/>
    * Data comparisons between April and June of 2020 and 2021<br/> 
    * Five stations within the zipcodes with highest COVID cases<br/>
    * Bar graphs of transit traffic in three stations on one subway line, between 7 pm and 7 am on weekdays, within the zip codes with the highest burden of COVID<br/>
 
