# Malaria Data Simulation

This Python script generates simulated data for malaria cases, incidence, treatment, and blood smears across various districts over a range of years. The data is stored in Pandas DataFrames.

## DataFrames

The script creates five different DataFrames:

1. **Blood Smears DataFrame (`blood_smears_df`)**: This DataFrame contains data about blood smears collected and examined, along with the results of the tests (positive or negative).

2. **Malaria Incidence DataFrame (`malaria_incidence_df`)**: This DataFrame includes data about the annual parasite incidence, slide positivity rate, annual blood examination rate, and the annual incidence of different types of malaria.

3. **Malaria Cases DataFrame (`malaria_cases_df`)**: This DataFrame holds data about the total number of malaria cases and the number of cases for each type of malaria.

4. **Malaria Treatment and Mortality DataFrame (`malaria_treatment_df`)**: This DataFrame contains data about the radical treatment of malaria and the total number of deaths due to different types of malaria.

Each DataFrame has a similar structure, with 'Year' and 'District' as common columns. The 'Year' column ranges from 2002 to 2023, and the 'District' column includes various districts of Rwanda.

## Usage

To use this notebook, you need to have Python installed along with the `pandas` and `numpy` libraries. You can run the script in a Python environment, and it will generate the DataFrames in that environment.