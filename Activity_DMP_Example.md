---
title: "Project Data - DMP"
author: "Haoran Xu"
date: "2024-10-20"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## ARTICLE INFORMATION
### Article Title
Future Mobility in Canada Survey (FMCS) dataset

### Authors
Darren Scott*, Haoran Xu

### Affiliations
McMaster University

### Corresponding author’s email address
scottdm@mcmaster.ca

### Abstract

A nationwide Canadian survey, called the Future Mobility in Canada Survey (FMCS), was designed to capture the complex decisionmaking processes of travel behavior changes and the adoption of new mobility tools by assessing individual preferences, affective motivations, and behavioral intentions. FMCS investigated four main areas: (1) respondents’ intentions to adopt AVs, (2) respondents’ use of shared forms of mobility services, (3) respondents’ recent experience with telework and their preferences towards it, and (4) respondents’ behavior across the COVID-19 pandemic for certain modes and telework. FMCS addressed these four areas by collecting responses from 5002 respondents between October and November 2021, across the five largest Canadian census metropolitan areas in terms of population (Toronto, Montréal, Vancouver, Ottawa-Gatineau, and Calgary) and Hamilton, which ranked 9th largest in 2021.   

### Keywords

Travel behavior; Individual preferences; Behavioral intentions; Canadian cities

## SPECIFICATION TABLE
  
Subject | Geography   
Specific subject area | Recording residents' perceptive travel behavior changes and their adoption of automated vehicles and mobility tools in major Canadian cities.   
Type of data | Table [raw] (Format_Original: XLS, Format_Generic: CSV)   
Data collection | The survey was programmed and administered by Savanta15 (a data and market research company), in both English and French, Canada’s official languages, using unique logical prompts to capture a stratified random sample with a minimum response burden, which is the third key strategy taken throughout the survey design and data collection processes.   
Data source location | The questionnaire was published online but targeted at people living in six Canadian cities (Toronto, Montréal, Vancouver, Ottawa-Gatineau, and Calgary and Hamilton).   
Data accessibility | Repository name: ... 
Data identification number: ...    
Direct URL to data: ...   
Related research article | Hamiditehrani, S., Scott, D.M. & Sweet, M.N. Design of the “Future Mobility in Canada Survey” (FMCS) to assess the evolving mobility landscape in urban Canada with an emphasis on automated vehicles. Transportation (2024). https://doi.org/10.1007/s11116-024-10484-7  

## VALUE OF THE DATA

-	First, to the best of our knowledge, this is the first survey to assess all types of AVs at a nationwide scale in Canada with a large sample size. Using FMCS, researchers could explore Canadian preferences towards any type of AV.   

- Second, the implementation of questions appraising behavioral intention towards AVs were sensitive to the AV types and prospective consumers’ demands.   

- Third, attitudinal questions exploring the affective motivations, which could influence any travel behavior changes and behavioral intention towards emerging mobility modes – namely, SAVs and PooledAVs – were the other novel facet of FMCS.   

- Fourth, the emphasis on detailed geography using six-digit postal codes of residences and workplaces helps identify the spatial context of potential markets for shared mobility services, telework, and any type of AV.   

- Finally, exploring the implications of the COVID-19 pandemic on current travel behavior and preferences towards telework at a nationwide scale, was another innovative aspect of FMCS.   

## BACKGROUND

Among the existing theoretical frameworks, TPB (Theory of Planned Behavior) is one of the most reliable and validated adoption theories. TPB contends that behavioral intention determines real behavior and acceptability and includes three components of intention to perform a behavior: attitude towards a behavior (ATB), subjective norms (SN), and perceived behavioral contro (PBC). Using an extended TPB framework, FMCS proposed a survey framework where additional affective motivations alongside TPB’s components are examined through various indices   

## DATA DESCRIPTION

- FMCS_dataset   
  - FMCS_Survey  
    - 1_FMCS_Consent (e.g., word file)  
    - 2_FMCS_ScreeningQuestions (e.g., word file)  
    - 3_FMCS_MainQuestionnaire (e.g., word file)  
  - FMCS_Survey_Results   
    - Survey_results_raw_2023-09-08 (e.g., csv file)   
  - Related_Research_Article  
    - Design_of_the_Future_Mobility_in_Canada_Survey_(FMCS)_to_assess_the_evolving_mobility_landscape_in_urban_Canada_with_an_emphasis_on_automated_vehicles (e.g., PDF file)  

## EXPERIMENTAL DESIGN, MATERIALS AND METHODS

### Sample Strategies

When designing FMCS, four key strategies were taken: (1) design an inclusive and representative survey, rather than focusing on specific population groups or mobility tool owners, (2) substitute a novel approach for stated preference (SP) to capture behavioral intentions towards adopting currently unavailable mobility tools, (3) use unique logical prompts to reduce respondent burden, and (4) design the survey based on a stratified random sampling approach. To ensure an inclusive and presentative survey, capturing a wide range of population segments throughout various geographical regions, along with assessing an extensive variety of existing and emerging mobility tools, a large sample was needed. A sample size of 5000 was determined as the maximum feasible within the project’s budget.  

### Survey pre‑testing and design refinement

FMCS underwent pre-testing to ensure its effectiveness and reliability. Prior to collecting the full sample, both a preliminary convenience sample of 50 observations and a pilot sur-vey involving 200 respondents were conducted. These initial stages aimed to identify and rectify potential issues with the survey instrument, such as ambiguous questions, response options, or definitions. The insights gathered from the convenience sampling and pilot survey informed crucial adjustments to the survey design, improving clarity, relevance, and overall respondent experience. For instance, in response to feedback obtained from the convenience sampling phase, a decision was made to employ the term “self-driving vehicle” instead of the recommended “automated vehicle” (AV) term as per the Society of Automotive Engineers’ taxonomy (SAE International 2021). This modification was imple-mented consistently across educational materials and associated survey questions. The choice to favor the term “self-driving vehicle” over “AV” was driven by observing that the former term was better understood than the latter term, highlighting the importance of aligning terminology with respondents’ understanding of concepts. In turn, this creates a more effective survey instrument.  

### Recruiting and incentives

After receiving research ethics approvals for FMCS through McMaster University (MREB # 2047) and Toronto Metropolitan University (REB # 2021–377), respondents were recruited from Savanta’s panel list through emails and online channels. Respondents were awarded loyalty points by Savanta, where the number of points received depended on the length of their engagement with the survey. The average incentive was CAD 1.10, where the incentive magnitude varied across population segments. For instance, since males are typically harder to recruit than females, the incentive for males was increased to achieve the target sample size. Also, older adults (56 years of age and over) prove harder to reach and their incentive was raised up to Can$6. In some CMAs such as Montréal, the recruitment rate was low and to achieve the target size, a higher incentive was considered. According to survey industry standards, respondents who abandoned the survey before completing it were not eligible to receive the incentive since they were aware of the topic, the estimated completion time, and the incentive amount before starting the survey.  

## LIMITATIONS

The survey could be improved by adding other aspects such as travel satisfaction and technology of communication people use. At the same time, an anonymized version of the data collected through the Future Mobility in Canada Survey would not be available until January 2027.   

## ETHICS STATEMENT

The research ethics for FMCS were approvals by McMaster University (MREB # 2047) and Toronto Metropolitan University (REB # 2021–377).

## CREDIT AUTHOR STATEMENT

Haoran Xu: ...; Darren Scott: ....

## ACKNOWLEDGEMENTS

The authors thank...

## DECLARATION OF COMPETING INTERESTS

The authors declare that they have no known competing financial interests or personal relationships that could have appeared to influence the work reported in this study.

## REFERENCES

Hamiditehrani, S., Scott, D.M. & Sweet, M.N. Design of the “Future Mobility in Canada Survey” (FMCS) to assess the evolving mobility landscape in urban Canada with an emphasis on automated vehicles. Transportation (2024). https://doi.org/10.1007/s11116-024-10484-7   
...

