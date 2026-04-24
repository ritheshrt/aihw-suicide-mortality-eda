

# AIHW Suicide Mortality - Exploratory Data Analysis\
\
Exploratory analysis of national suicide mortality trends in Australia \
using AIHW National Mortality Database data (2024 release), examining \
patterns by sex, age group, remoteness area, and psychosocial risk factors \
across five analytical perspectives.

## Background
\
Suicide is the leading cause of death for Australians aged 15 to 44 and \
a significant focus of national mental health strategy. This project uses \
publicly available AIHW surveillance data to explore demographic and \
geographic patterns in suicide mortality, with the aim of identifying \
population groups and risk profiles relevant to prevention policy.

## Key Findings

  Using AIHW National Mortality Database (NMD) data in April 2026, covering ICD-10 codes X60-X84, Chart 1 shows female suicide rate peaking in 1971 at 10.4 and then plateauing to around 5-6 per 100 000 since 1980 whereas the male suicide rate peaked in the 1990s (1997 at 23.7), plateauing at around 18 - 20 from 2014 onwards. During this time, the male: female suicide ratio has remained constant at around 3:1. The Very Remote and Remote communities have consistently recorded a higher suicide rate than those in Major Cities (in 2024, it was 39.6 and 39.2 vs 15.2 in Major Cities at a ratio of ~2.6x). There has been a rise in youth suicides since 2004 for 15 - 17 and 5 - 17 age groups and from 2009 for 18 - 24 age group to a peak around 2020/2021. One limitation of this is that we do not have the ability to contextualise current youth rates against the broader historial trend seen in NMD1 for the national series (the rate dropped during the 2000s for all age groups but we cannot deduce whether 2001 was the peak or prior to 2001. A disclaimer too is that 2023 and 2024 are preliminary date (ie coronial lag would indicate that those years are undercounts). The rate of suicides is higher than rates from alcohol and drug-related despair for men, although upto around the mid-late 2000s, the rate of deaths from alcohol related offences was higher than that from drug related offences (rise of deaths from opioid overdoses coincide from this time onwards). All sexes and all age groups have the highest psychosocial risk factor of death from a personal history of self-harm, which is clinically significant and consistent with clincial literature research on this topic.
  
## Data Source
\
Australian Institute of Health and Welfare (AIHW), National Mortality \
Database: Suicide and Self-harm Monitoring, published April 2026.  \
ICD-10 codes: X60-X84, Y87.0.  \
Available at: https://www.aihw.gov.au/suicide-self-harm-monitoring/data/suicide\
\
Tables used: NMD 1, NMD 5, NMD 13a, NMD 16, NMD 17.\
\
The raw data file is not included in this repository. Download it from \
the link above and place it in the Data/ folder before running the notebooks.

## How to Run

Install dependencies with `pip install -r requirements.txt`. Download the \
AIHW Excel file from the link above and place it in the Data/ folder. \
Run the notebooks in order: 01_data_exploration, 02_data_cleaning, \
03_analysis_visualisation. Each notebook is self-contained with explanatory \
markdown cells throughout.

## Limitations

Deaths registered in 2023 and 2024 are based on preliminary data subject \
to coronial revision, rates in those years may undercount actual suicide \
deaths. Cells marked n.p. in the source data indicate suppressed small counts \
and are treated as missing rather than zero throughout this analysis. \
NMD 17 covers 2017-2024 only, limiting trend analysis for psychosocial \
risk factors. All findings are observational, no causal inference is drawn.