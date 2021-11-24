Analysis of Global COVID-19 Pandemic Data

TASK 1: Get a COVID-19 pandemic Wiki page using HTTP request
First, let's write a function to use HTTP request to get a public COVID-19 Wiki page.
Before you write the function, you can open this public page from this
URL https://en.wikipedia.org/w/index.php?title=Template:COVID-19_testing_by_country using a web browser.
The goal of task 1 is to get the html page using HTTP request (httr library)

TASK 2: Extract COVID-19 testing data table from the wiki HTML page
On the COVID-19 testing wiki page, you should see a data table <table> node contains COVID-19 testing data by country on the page:
The goal of task 2 is to extract above data table and convert it into a data frame
Now use the read_html function in rvest library to get the root html node from response

TASK 3: Pre-process and export the extracted data frame
The goal of task 3 is to pre-process the extracted data frame from the previous step, and export it as a csv file

TASK 4: Get a subset of the extracted data frame¶
The goal of task 4 is to get the 5th to 10th rows from the data frame with only country and confirmed columns selected

TASK 5: Calculate worldwide COVID testing positive ratio¶
The goal of task 5 is to get the total confirmed and tested cases worldwide, and try to figure the overall positive ratio using confirmed cases / tested cases

TASK 6: Get a country list which reported their testing data
The goal of task 6 is to get a catalog or sorted list of countries who have reported their COVID-19 testing data

TASK 7: Identify countries names with a specific pattern
The goal of task 7 is using a regular expression to find any countires start with United

TASK 8: Pick two countries you are interested, and then review their testing data¶
The goal of task 8 is to compare the COVID-19 test data between two countires, you will need to select two rows from the dataframe, and select country, confirmed, confirmed-population-ratio columns

TASK 9: Compare which one of the selected countries has a larger ratio of confirmed cases to population¶
The goal of task 9 is to find out which country you have selected before has larger ratio of confirmed cases to population, which may indicate that country has higher COVID-19 infection risk

TASK 10: Find countries with confirmed to population ratio rate less than a threshold
The goal of task 10 is to find out which countries have the confirmed to population ratio less than 1%, it may indicate the risk of those countries are relatively low