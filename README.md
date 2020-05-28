# Indeed Consulting
 
 My contributions to the UC Berkeley Student Association for Applied Statistics' Spring 2020 Data Consulting project for Indeed
 

## Methods:

Obtain BLS data from https://www.bls.gov/oes/tables.htm
* Merge metropolitan and non-metropolitan datasets for desired years and clean data using R

Obtain Congressional voting record data from https://voteview.com/data
* Clean data, paying special attention to the fact that date formatting changes partway through the dataset


Obtain GDP data from https://www.imf.org/external/pubs/ft/weo/2020/01/weodata/weorept.aspx?sy=1960&ey=2021&ssm=1&scsm=1&ssd=1&sort=country&ds=.&br=1&pr1.x=30&pr1.y=7&c=111&s=NGDP_RPCH%2CPPPGDP%2CNGDPRPPPPCPCH%2CPCPIPCH%2CPCPIEPCH%2CLUR%2CGGXCNL_NGDP%2CBCA_NGDPD&grp=0&a=#download
* Clean data, transposing the dataset to orient the columns appropriately

Obtain OECD Consumer Confidence Index data from https://data.oecd.org/leadind/consumer-confidence-index-cci.htm=
* Clean data

Merge datasets on year and generate linear regression models to explore whether the number of bills passed and other economic data can be used to predict the change in employment totals for a given year.
