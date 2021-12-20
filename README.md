# Gender and Tenure Diversity 

Even though we live in a STEM world powered by technologies the gender discrimination still exists. This is not just a random guess that females feel less welcomed in the Software industry, but it is a proven fact because many females and even males think the same about their female colleagues. It should often be considered that some feminine influence is indeed needed in the software world along with the masculine influence. Females are considered better coders than men, many studies have proven this, but still, their consideration is the bare minimum in this well-known technology-driven world. In the world we see today where one side we are moving to a more advanced and developed work of Science and Technology but we are still lagging behind in terms of including diversity in the jobs bringing the revolution today. Most of the discrimination that is faced in the Technical world today is mostly on the basis of one type of diversity that is gender diversity. This is the reason that in this project the main focus is covering the concern of gender inclusion in various perspectives in the Software industry today.

### Data Collection

Two main parts of Data Cllection were:
* GHTorrent - GitHub's Data Repository
* Gender guesser - to get data of gender of users.

### Research questions

* What is the male to female ratio in projects?
* Relation of Gender diversity with the project tenure.
* Does gender diversity depend on team size (no. of contributors).

### Data Analysis 

Data Analysis is done in two ways:
* Data Visualization
* Statistical modelling using one way ANOVA

### Files in Directory

* Data - Containing all the the data used after final pre-processing and web scrapping phases.
  * Projects_tenure_size_gender_dataset.csv - File containg the project's data correlated to all the users and gender information, classified according to Project tenure and team size.
  * Main_Users_data.csv - File containing the project's data related to the users and their genders.
  
* Program Files - Files containing all the codes from Clasification to final analysis.
  * Users_Fullnames_extraction.ipynb - Containg the code used for finding fullnames of users (by using web scraping on github.com)
  * Users_gender_classification.ipynb - Containing the code used for generating the gender of users (by using gender-guesser)
  * ProjectTenure_Teamsize_classification.ipynb - Containing the data classification done on the basis of Project Tenure and team sizes.
  * Main_Data_Analysis.ipynb - Containing the whole code for the final analysis.

* Analysis Results - Containing at glance the results generated from the Final Analysis.

###### Replication : 24.	Vasilescu, B., Posnett, D., Ray, B., van den Brand, M. G., Serebrenik, A., Devanbu, P., & Filkov, V. (2015, April). Gender and tenure diversity in GitHub teams. In Proceedings of the 33rd annual ACM conference on human factors in computing systems (pp. 3789-3798).
