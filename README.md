{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # AIHW Suicide Mortality -- Exploratory Data Analysis\
\
Exploratory analysis of national suicide mortality trends in Australia \
using AIHW National Mortality Database data (2024 release), examining \
patterns by sex, age group, remoteness area, and psychosocial risk factors \
across five analytical perspectives.\
\
## Background\
\
Suicide is the leading cause of death for Australians aged 15 to 44 and \
a significant focus of national mental health strategy. This project uses \
publicly available AIHW surveillance data to explore demographic and \
geographic patterns in suicide mortality, with the aim of identifying \
population groups and risk profiles relevant to prevention policy.\
\
## Key Findings\
\
- [Your Chart 1 finding -- the male peak in 1997, economic context, 3:1 ratio]\
- Age-standardised male suicide rates in Very Remote areas (39.6 per 100,000 \
  in 2024) are approximately 2.6 times those in Major Cities (15.2), a gap \
  that has persisted across the full 2001-2024 observation period.\
- [Your Chart 3 finding -- youth trend, 2004 onwards, COVID caveat]\
- [Your Chart 4 finding -- deaths of despair, opioid convergence]\
- Personal history of self-harm (ICD-10 Z915) was the most frequently \
  documented psychosocial risk factor across all sex and age group \
  combinations in 2024, consistent with international literature on \
  suicide risk stratification.\
\
## Data Source\
\
Australian Institute of Health and Welfare (AIHW), National Mortality \
Database -- Suicide and Self-harm Monitoring, published April 2026.  \
ICD-10 codes: X60-X84, Y87.0.  \
Available at: https://www.aihw.gov.au/suicide-self-harm-monitoring/data/suicide\
\
Tables used: NMD 1, NMD 5, NMD 13a, NMD 16, NMD 17.\
\
The raw data file is not included in this repository. Download it from \
the link above and place it in the Data/ folder before running the notebooks.\
\
## How to Run\
\
Install dependencies with `pip install -r requirements.txt`. Download the \
AIHW Excel file from the link above and place it in the Data/ folder. \
Run the notebooks in order: 01_data_exploration, 02_data_cleaning, \
03_analysis_visualisation. Each notebook is self-contained with explanatory \
markdown cells throughout.\
\
## Limitations\
\
Deaths registered in 2023 and 2024 are based on preliminary data subject \
to coronial revision -- rates in those years may undercount actual suicide \
deaths. Cells marked n.p. in the source data indicate suppressed small counts \
and are treated as missing rather than zero throughout this analysis. \
NMD 17 covers 2017-2024 only, limiting trend analysis for psychosocial \
risk factors. All findings are observational -- no causal inference is drawn.}