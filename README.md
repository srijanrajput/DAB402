# DAB402
Capstone projecct

# Prequisite
1. Need Python and pip installation
2. Need R and R studio to run the files.

# Installing Python and Jupyter
1. Go to python installation website and install python > 3
2. With python installed in the system there should be 'pip' command avaiable from the terminal
3. use pip to install jupter notebook 
4. Run `jupyter notebook` on the terminal
5. This will open the page on browser with file explorer. Use the explorer here to open the `.ipynb' file.
6. Correct the path for the source file
![MicrosoftTeams-image (1)](https://user-images.githubusercontent.com/9460937/137208874-01e4aa06-d2ff-4c30-9b07-44bfb10c474e.png)
8. From the top menu use `Run`->`Run all cells`


# Installing R and R studio
1. Install R and R studio using the download link `https://rstudio-education.github.io/hopr/starting.html`
2. Once installed open `R studio` and using `R studio` open `.Rmd` File.
  ![MicrosoftTeams-image](https://user-images.githubusercontent.com/9460937/137208913-7bc6655b-b505-4201-886f-9990f837b0f9.png)
3. Install all the suitable libraries for R and R studio. Sometimes there is warning shown on the top of R studio.
4. Run all cells as shown below:
  ![image](https://user-images.githubusercontent.com/9460937/137209382-c79db713-3999-4377-abab-c31ce8b6306d.png)


# Data

Data have 2240 observations and 29 attributes, which mainly includes the customers’ attributes, amount spend on products, campaign techniques. 

 

# Attributes 

## People 

**ID:** Customer's unique identifier -  `[ID] `

**Year_Birth:** Birth year of customer - `[Year] `

**Education:** Education level of customer `['Graduation',` 'PhD', 'Master', 'Basic', '2n Cycle'] 

**Marital_Status:** Marital status of customer `['Single',` 'Together', 'Married', 'Divorced', 'Widow', 'Alone’, ‘Absurd', 'YOLO'] 

**Income:** Yearly income of customer `[1732 to 666666`] 

**kidAtHome:** Number of children in customer's household `[0-2]` 

**teenAtHome:** Number of teenagers in customer's household.  `[0-2]` 

**dt_Customer:** Date of customer's enrollment with the company `[Date] `

**Recency:** Number of days since customer's last purchase `[0-99]` 

**Complain:** 1 if customer complained in the last 2 years, 0 otherwise 

 

## Products 

**amtWines**: Amount spent on wine in last 2 years `[0-1493 in` USD] 

**amtFruits**: Amount spent on fruits in last 2 years `[0-199 in` USD] 

**amtMeatProducts**: Amount spent on meat in last 2 years `[0-1725 in` USD] 

**amtFishProducts**: Amount spent on fish in last 2 years `[0-259 in` USD] 

**amtSweetProducts**: Amount spent on sweets in last 2 years `[0-263 in` USD] 

**amtGoldProds**: Amount spent on gold in last 2 years `[0-362 in` USD] 

 

## Promotion 

**noDealsPurchases**: Number of purchases made with a discount `[0-15%`] 

**AcceptedCmp1**: 1 if customer accepted the offer in the 1st campaign, 0 otherwise   `[0,1]` 

**AcceptedCmp2**: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise `[0,1]` 

**AcceptedCmp3**: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise `[0,1]` 

**AcceptedCmp4**: 1 if customer accepted the offer in the 4th campaign, 0 otherwise `[0,1]` 

**AcceptedCmp5**: 1 if customer accepted the offer in the 5th campaign, 0 otherwise `[0,1]` 

**Response**: 1 if customer accepted the offer in the last campaign, 0 otherwise `[0,1]` 

 

## Place 

**noWebPurchases**: Number of purchases made through the company’s web site `[0-15]` 

**noCatalogPurchases**: Number of purchases made using a catalogue `[0-28]` 

**noStorePurchases**: Number of purchases made directly in stores `[0-13]` 

**noWebVisitsMonth**: Number of visits to company’s web site in the last month `[0-20]` 

  

The data has **3 Categorical attributes i.e. Education, Marital_Status** and Dt_Customer and **26** are numerical. 


# Context: 

The purpose of analysis would be to work on target marketing and in order to achieve that we’ll start by performing clustering for customer segmentation. Clustering is a useful technique for dividing the data points in several groups in such a way that each data point in the same group holds similar properties as compared to data points in the other groups. 

