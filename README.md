# R-Coding Project Proposal : Exploring social mobility patterns across generations of Italian Households  

#Data Description:

#The folder contains two excel files downloaded from the Bank of Italy reporting the data from the
survey on the Household Income and Wealth in Italy in different years.
These are cross-sectional microdata on Italian Households containing the results of the same survey run
with slightly different questions across years but containing the same core information interesting for
my analysis.

#From the File called Tables_2020 I would like to use Table 7bis and Table 5, but for now I’m uploading
the all series because I’m still not completely sure if the variables needed in my analysis are all inside
these two tables.

#Table 5 contains data on: the Mean equivalent income and expenditure and Poverty Indexes for Italian
Households with different demographic characteristics. Specifically the data contains the Equivalent
Income, Equivalent expenditure and the per capita income for different levels of education, branches of
activity, work status ,agse and the genders in 2020.

#Table 7/bis reports the division of Italian Households in quintiles with respect to income.
From the FIle called Historical_tables I would like to use Table S12 containing informations on the
mediam family income by characteristics of the households as: gender, age, title of study, professional
condition, place of origin geographic area of residence for years from 1977 to 2020.

#Data on 2020 are in both datasets but I would like to use both because the Table_2020 I think has better
data on a single year while Historical_tables has longitudinal data but less interesting informations so I
will use the two datasets for different part of the analysis.

#The Research questions:
1. To which extent there is intergenerational social mobility among Italian households?

2. How social mobility patterns differ across demographics and socioeconomic groups as education
level, occupation and regional location?

3. How social mobility patterns evolved over time ?

#The planned analysis:
The purpose of this research plan is to explore social mobility patterns across generations of Italian
households in different demographic and socioeconomic cathegories from year 1977 to 2020.

#I would like first of all to divide the sample in generations (1,2,3,4) and then to run OLS log-log models
using as a dependent variable the Household income and as Independent variables the Generation, the
level of education, the level of education, the occupation, the log of the wealth, the age and the gender
of the household head in addition to the number of children present in the family.
With my regressions I would like to predict income based on the characteristics of the households and
then to store the results in social mobility matrices reporting the probability to pass from one quintile to
the other of the population in different generations and across different demographic and
socioeconomic characteristics.In addition I would like to plot trends for different groups across time.

