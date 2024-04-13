# Curiosity-Saved-Cat
# Problem Statement:

Limited registered Veterinary Surgeons (30,000) compared to pet population (10.7 million cats, 9.6 million dogs) in the UK.
Time constraints lead to inconsistent, shorthand patient notes among vets, hindering trend analysis.
Potential data insights remain untapped due to inconsistent note-taking practices.
# Stakeholders & Users:
Veterinary Surgeons
Veterinary Nurses
Practice Manager
Clinical Director
Students:
Software Developers
Data Scientists
Customer – Practice Director
Customer Requirements:

# Methodology Development:
# Data Pre-processing:

1. Cleanse data using Pandas in Python.
2. Handle null values, standardize abbreviations, and format text.
# Natural Language Processing (NLP):
-> Utilize SpaCy and ScispaCy libraries to extract terms like diseases, treatments, drugs, and symptoms.
# Dashboard and Querying System Development:
-> After cleansing the data, I uploaded the file to Power BI where I created an interactive dashboard and querying system for Consult ID,filters for species, vaccine search, symptoms, and disease search. I also developed visualizations for the count of cases registered by species, the count of cases registered each year, the count of cases registered each month, and the count of vaccines used by SAVSNET MPC. 
-> In the dashboard, I created 3 pages. On the first page, it shows the title of the project which is shown below. 
![page1](https://github.com/Sowjanya69/Curiosity-Saved-Cat/assets/79791890/212c1c08-a4f0-458c-be2c-8df92731daa4)

-> On the second page, I have shown the search engine for all consult IDs, Diseases, Vaccines, and All chemicals. It shows all the information of ID, disease, vaccine, and drug and also species affected if we searched for any of the above particulars. The page looks like below.

![page2](https://github.com/Sowjanya69/Curiosity-Saved-Cat/assets/79791890/ad120168-3bf9-402a-b0e4-4308acc29a2e)

-> On the third page, I made all the analyses and visualizations like the count of cases registered by species, the count of cases registered each year, the count of cases registered each month, and the count of vaccines used by SAVSNET MPC. It is dynamic and if we select any particular it will show all the fields and also we can select a particular date by the use of the toggle bar. The page looks like below. 

![page3](https://github.com/Sowjanya69/Curiosity-Saved-Cat/assets/79791890/4b819e0f-e424-4049-8098-60f3dd93444c)

Making a dashboard like the above images allowed veterinary doctors and nurses to search for relevant patient information.

# Conclusion:
The project successfully streamlined data analysis by following an Extract, Transform, and Load (ETL) process, empowering veterinary professionals to make informed decisions based on standardized, accessible patient information.
