# Novel-Corona
Context 
From World Health Organization:  
On 31 December 2019, WHO was alerted to several cases of pneumonia in Wuhan City, Hubei Province of China.  
The virus did not match any other known virus. This raised concern because when a virus is new, we do not know how it affects people. 
So daily level information on the affected people can give some interesting insights when it is made available to the broader data science community.  Johns Hopkins University has made an excellent dashboard using the affected cases data.  
Data is extracted from the Google Sheets associated and made available here.   
Uploading it here for using it in Kaggle kernels and getting insights from the broader DS community.  Content 2019 Novel Coronavirus (2019-nCoV) is a virus (more specifically, a coronavirus) identified as the cause of an outbreak of respiratory illness first detected in Wuhan, China. Early on, many of the patients in the outbreak in Wuhan, China reportedly had some link to a large seafood and animal market, suggesting animal-to-person spread. However, a growing number of patients reportedly have not had exposure to animal markets, indicating person-to-person spread is occurring. At this time, it’s unclear how easily or sustainably this virus is spreading between people - CDC  This dataset has daily level information on the number of affected cases, deaths and recovery from 2019 novel coronavirus. Please note that this is a time series data and so the number of cases on any given day is the cumulative number.   

The data is available from 22 Jan, 2020.  Column Description Main file in this dataset is covid_19_data.csv and the detailed descriptions are below.  covid_19_data.csv  Sno - Serial number ObservationDate - Date of the observation in MM/DD/YYYY Province/State - Province or state of the observation (Could be empty when missing) Country/Region - Country of observation Last Update - Time in UTC at which the row is updated for the given province or country. (Not standardised and so please clean before using it) Confirmed - Cumulative number of confirmed cases till that date Deaths - Cumulative number of of deaths till that date Recovered - Cumulative number of recovered cases till that date 2019_ncov_data.csv  This is older file and is not being updated now. Please use the covid_19_data.csv file  Added two new files with individual level information  COVID_open_line_list_data.csv This file is obtained from this link  COVID19_line_list_data.csv This files is obtained from this link  Country level datasets If you are interested in knowing country level data, 

please refer to the following Kaggle datasets:  
India - https://www.kaggle.com/sudalairajkumar/covid19-in-india  
South Korea - https://www.kaggle.com/kimjihoo/coronavirusdataset  
Italy - https://www.kaggle.com/sudalairajkumar/covid19-in-italy  
Brazil - https://www.kaggle.com/unanimad/corona-virus-brazil  
USA - https://www.kaggle.com/sudalairajkumar/covid19-in-usa  
Switzerland - https://www.kaggle.com/daenuprobst/covid19-cases-switzerland  
Indonesia - https://www.kaggle.com/ardisragen/indonesia-coronavirus-cases  
Acknowledgements:  
Johns Hopkins University for making the data available for educational and academic research purposes  
MoBS lab - https://www.mobs-lab.org/2019ncov.html  
World Health Organization (WHO): https://www.who.int/ DXY.cn. Pneumonia. 2020. http://3g.dxy.cn/newh5/view/pneumonia.  
BNO News: https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/  
National Health Commission of the People’s Republic of China (NHC): http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml  
China CDC (CCDC): http://weekly.chinacdc.cn/news/TrackingtheEpidemic.htm  
Hong Kong Department of Health: https://www.chp.gov.hk/en/features/102465.html  
Macau Government: https://www.ssm.gov.mo/portal/ Taiwan CDC: https://sites.google.com/cdc.gov.tw/2019ncov/taiwan?authuser=0  
US CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html  
Government of Canada: https://www.canada.ca/en/public-health/services/diseases/coronavirus.html  
Australia Government Department of Health: https://www.health.gov.au/news/coronavirus-update-at-a-glance  
European Centre for Disease Prevention and Control (ECDC): https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases  
Ministry of Health Singapore (MOH): https://www.moh.gov.sg/covid-19  
Italy Ministry of Health: http://www.salute.gov.it/nuovocoronavirus  
Picture courtesy : Johns Hopkins University dashboard 
Inspiration: some insights could be changes in number of affected cases over time change in cases over time at country level. Latest number of affected cases.
