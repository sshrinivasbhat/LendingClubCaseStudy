# Lending Club Case Study
> The data containing the  past loan applicants and whether they ‘defaulted’ or not is provided.
>The aim is to identify patterns which indicate if a person is likely to default,
>which may be used for taking actions such as denying the loan, reducing the amount of loan,
>lending (to risky applicants) at a higher interest rate, etc.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
Lending club has 2 main Functions
1.Providing the borrowers a way to apply for the loan
2.Having a environment for investors to fund these loans.
There are 3 Parties invloved in the lending club
1.Borrower - Who applies for a loan for the specific purpose
2.Lending Club - Based on the category,purpose,grades,sub-grades.. etc approves the loan amount which may be less than or equal to the applied loan from the borrower.
3.Investor - Who decides to invest in the specific loan portfolio's with various risk categories. Investor may decide on investing in the loan amount equal to or less than the approved loan amount from the lending club.
- What is the business probem that your project is trying to solve?
Understand the Consumer Attributes and Loan Attributes and analyse its influence on the tendency of default. The customers labelled as 'charged-off' in loan_status are the 'defaulters'.
Idenfify patterns to indicate the person defaulting , which may be further used to take decisions like denying the loan,reducing the loan amount, higher interest rates to risky applicants
- What is the dataset that is being used?
Information about past loan appicants and whether they defaulted or not.(loan.csv)
Data dictionary file which provides the description of various attributes (Data_dictionary.xls)
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The interest rates,grades and sub-grades,the term of the loan,annual income of the borrowers,purpose of the loan seems to show a significant contribution in tendency of default.
- The demographic variables like zip-code,state are not able to find any influence on the borrowers tendency to default.
- Grade of the borrower is used as a criteria for deciding the interest rates. 
- Other attributes of the borrowers like employment length(Experience),his home ownership status doesnt seem to influence borrowers tendency to default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Anaconda - Jupiter-Notebook
- Git and Github
- Python
- library - Panda  - version 1.0
- library - Matplotlib	 -version 2.0
- library - numpy -version 3.0
- library - Seaborn -version 3.0
- library - plotly -version 3.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project is the first mini project 
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@sshrnivasbhat] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->