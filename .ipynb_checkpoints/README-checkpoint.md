# FOCUSED Collaboration Project Artifacts
This is repo to hold reports and artifacts from the FOCUSED Collaboration Project. 

* [Project Overview](/Overview.md) - This contains most of the original project proposal text and gives a good outline of what this project is about.
* OSPO Classification Methodology - Coming Soon
* OSPO Classification Results - Coming Soon

## Data Sources
1. Suzy's classification
    - 2021-05-07
    - Google Sheet
1. [OSPO Landscape](https://landscape.todogroup.org) (Open Source Program Office)
    - 2022-05-09
1. [OSCI](https://opensourceindex.io) (Open Source Contributor Index)
    - 2022-02-28 (diff)
    - Emailed request for data (Apr 8)
1. [S&P 500](https://github.com/datasets/s-and-p-500-companies/blob/master/data/constituents.csv) (Standard and Poor's 500). The S&P 500 is a free-float, capitalization-weighted index of the top 500 publicly listed stocks in the US (top 500 by market cap). 
    1. 2021-10-05
    
    
## Summary
1. in_osci:  298 rows
1. in_sp500: 505 rows  (osci + sp500        =  781 rows)
1. in_suzy:  141 rows  (osci + sp500 + suzy =  876 rows)
1. in_ospo:  102 rows  (osci + sp500 + suzy + ospo =  919 rows)
    - alldata: 225 rows, but 117 unique ** NEED TO DISCUSS **  (sum of above        = 1039 rows) ==> 931 unique "company"
    - taking "OSPO Adopters" (not the full dataset that was downloaded)
    - cleaned up data: got 102 adopters, 101 unique (GitLab has entries for US and China)

OSCI: domain name for countries:  https://github.com/epam/OSCI/blob/master/osci/preprocess/match_company/company_domain_match_list.yaml
    

## To Do
### NEXT STEPS
- sort and check company names
- add in missing country names

- Fill in missing countries:  https://github.com/epam/OSCI/blob/master/osci/preprocess/match_company/company_domain_match_list.yaml
- double check company names, spot check for duplicates: export to Excel and check there
- look at Lux
- looking at summaries
- Suzy list: member list from To Do list possibly from here (https://github.com/todogroup/governance/blob/main/MEMBERS.csv)
  - related to members, not adopters
- Jekyll blog
- do plotly graphs (use function); do histograms; account for missing data
- Clean up sectors (Ex: For "sector", replace "Information Technology" with "Technology")
- need to map out graphs
- S&P 500:  how many S&P 500 are in OSCI?


## Tasks Done
- 2022-05-22:  
    - For OSPO dataset, only take "Adopters" (not Members and all)
    - rename vars in ospo dataframe: DONE
    - merge ospo data in: DONE
    - Assign S&P records to country="United States" DONE
- Watch Lux video:  https://youtu.be/O28RZ8SsSQk
- Run Lux examples with this dataset:  

## Questions to ask
1. What percentage of the S&P 500 companies are present in the OSCI dataset?

S&P as an anchor:
countries, compare to maybe a EU dataset
high in OSCI (such as top 10 contributors), but not in OSPO "adopters" (but don't have an OS program), would be interesting to know
How to get a sense of maturity for these open source offices?
Maybe Germany or EU has its own list of companies
Those in OSCI and OSPO high may participate in the program.  And if everyone says no, we can pivot
Assessing maturity of program: look at results and sort into cohorts.
5 companies that are very mature, this is their collaboration pattern.  Here are 5 orgs that are making individual contributions but they are not releasing things of their own.  If no one participates in survey, but we 


## References
- https://www.datahub.io/core/nyse-other-listings#data-cli


