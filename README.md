Analysis of TLTRO Impacts on Loan Stocks of Eurozone's Five Largest Economies

Research Question: How significantly did ECB’s TLTRO program effect the five biggest Eurozone economies’ loan stocks?  
Data Source: European Central Bank (ECB), Statistical Data Warehouse  
Scope: Germany, France, Italy, Spain, the Netherlands  
Time Period: 1997-2025 (TLTRO I-II-III: 2014-2022)  
Main Metrics: Loan Stock Volumes and Growth Rates  
Tools: Microsoft Excel, SQL (MySQL), Tableau  

Project Objective

This analysis examines the impact of the European Central Bank's (ECB) Targeted
Longer-Term Refinancing Operations (TLTRO) program on the loan stocks of the five
largest economies in the Eurozone (Germany, France, Italy, Spain, and the
Netherlands). The main objective is to analyze quarterly credit stocks from 1997 to
2025 to provide information on how the program differs in its impact across the five
major European economies. The project focuses on three different TLTRO phases (I:
2014-2016, II: 2016-2019, III: 2019-2022).


Methodology

1. Obtaining quarterly total credit stock data from the ECB Statistical Data
Warehouse for the period 1997Q3 to 2025Q3
2. Cleaning and structuring 560+ quarterly data points using SQL
3. Calculating quarter-over-quarter growth rates, absolute changes and period
comparisons by using window functions, CTE (Common Table Expression) in SQL
4. Creating 14 graphs/charts which show country-level trends, aggregate patterns,
and comparative metrics across the five economies by using Tableau

Key Findings

- Germany and France experienced strong credit expansion during TLTRO periods
(+34.8% and +45.1% respectively, 2014-2022), while Italy and Spain contracted
(-8.3% and -18.2%).
- The Netherlands did not experience any noticeable change.
- TLTRO-III (2019-2022) showed the strongest correlation with credit growth across
all countries.

Project Structure

tltro-impact-analysis/  
├──- sql/ # SQL queries for analysis  
├──- data/ # Sample dataset  
├──- tableau/ # Tableau visualisations  
├──- report/ # Analysis report in PDF format  
└──- README.md # Project documentation  

1. Review SQL queries in the /sql folder for analysis methodology
2. Open Tableau files in /tableau to explore tableau visualisations
3. Read the full analysis in /Project

License

This project is for portfolio and educational purposes. Data from the European Central Bank (ECB) Statistical Data Warehouse is used in accordance with transparency exercise guidelines.

Author

- Mert Cevher
- Master's Student in Public Economics, Law and Politics
- www.linkedin.com/in/mertcevher | mert.cevher@stud.leuphana.de
