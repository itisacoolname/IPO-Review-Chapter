# IPO Review Chapter: "Initial public offering: A synthesis of the literature and directions for future research" 
This directory explains in details how to extract IPO data from SDC Platinum database, match it with CRSP and produce main statistics.
These codes and the final data sample is used in Lowry, Michaely and Volkova, 2017, "Initial public offering: A synthesis of the literature and directions for future research", in Foundations and Trends in Finance (working paper avaliable at https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2912354)

## **Before going over the codes please review 1. IPO Online Appendix.pdf file**

This file provides extensive explanation of the data collection and cleaning. 
The file explains objective of each step in the data cleaning process. While this file mostly uses R code for references we've tried to provide detailed textual explanation of each step for non-R users as well.

**1. Pull IPO Data from SDC**
This folder contains:
 - The document that explains step by step extraction of data from SDC ("Extraction data from SDC.docx")
 - Saved SDC session ("SDC_session.ssh") that could be load to track our data selection
 - SDC report ("sdc_report.rpt") that extracts all the variables used 

**2. Clean SDC Request**

- This folder contains script that clean SDC request and matches it with CRSP data

**3. Construction of IPO Statistics**

- This folder contains script that produce all the graphs in Lowry, Michaely and Volkova (2017)


**4. Resulting Tables and Figure**

- This folder has Excel files of figures and tables as presented in Lowry, Michaely and Volkova (2017)
