# Replication Project for the Course "Causal Inference and Predictive Modeling"

Replication project of the paper [Angrist, J., Lang, D., and Oreopoulos, P. (2009). Incentives and Services for College Achievement: Evidence from a Randomized Trial. *American Economic Journal: Applied Economics*, 1(1), 136-163.](https://www.aeaweb.org/articles?id=10.1257/app.1.1.136)

### Data Files
STAR_public_use.dta: STATA data files are used for Figure 1 and Table 1 to Table 8, except Table 4.

### R Replication Code
The R replication code is used to generate the results reported in the term paper.
1. empirics_replication.R: This R program is used to replicate all estimated results from this paper.
2. empirics_replication.html: html file shows all the programming details with the associated R code.

Please note that few `Stargazer` codes have been hidden in html file and I only show the regression results. For more details, please check the R code.
 
### STATA Code and Dofiles
'STARdatapost' folder contains the following list of the STATA code used to prepare the data and conduct the analysis in their paper. Logfile is enclosed. The code is available on the author’s [homepage](https://economics.mit.edu/faculty/angrist/data1/data/angrist,1) and also the web page of [American Economic Association](https://www.aeaweb.org/articles?id=10.1257/app.1.1.136).

1. STAR Figure1.do: This STATA program creates 'Figure 1a and Figure 1b: Normalized First-Year
GPA'
2. STAR Table1.do: This STATA program creates 'Table 1-Descriptive Statistics'
3. STAR Table2.do: This STATA program creates 'Table 2-Selection Effects'
4. STAR Table3.do: This STATA program creates 'Table 3-Program Sign-up and Use of Services'
5. STAR Table5.do: This STATA program creates 'Table 5-Treatment Effects on First Year Outcomes
in the Sample with Fall Grades'
6. STAR Table6.do: This STATA program creates 'Table 6-Treatment Effects on First and Second Year
Outcomes'
7. STAR Table7.do: This STATA program creates 'Table 7-OLS and Quantile Treatment Effects on
GPA (Stacked)'
8. STAR Table8.do: This STATA program creates 'Table 8-2SLS Estimates for Women (Stacked)'

### Note
The paper has a coding error in the Table 5 - Treatment Effects on First Year Outcomes in the Sample with Fall Grades. They would like to report estimates from models that pool SFP and SFSP treatment groups into a single ”any-SFP” effect, since fellowship treatments produced substantial and significant effect on fall grades. However, They pooled SSP and SFSP treatment groups into a single ”anySFP” effect.
