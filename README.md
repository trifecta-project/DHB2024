# DHB2024
Repo for DHBenelux 2024 submission "Smoke and mirrors: Tracking the Influence of the Opium Trade in the Dutch East India Company through Letters and Cargo Logs"

# Instructions

1. Preparing the data
   
   1.1. Download the cleaned corpus of General Missive (GM) letters at https://github.com/CLARIAH/wp6-missieven/tree/d4a1683f62c987cb4454c8614059a0036d623fec/xml (all folders, from 01 to 14)
   
   1.2. Run the notebook '[0] Parsing the GM letters.ipynb' to parse the GM letters and save the result
   
   1.3. Download the Bookkeeper General Batavia (BKB) dataset at https://resources.huygens.knaw.nl/bgb/search (todo: ask Marieke how exactly did we get the spreadsheets from there)
   
   1.4. (optional) Run the notebook 'BGB_initial_analyses.ipynb' to explore the dataset
   

3. Find the occurrences of opium and main spices (pepper, cinnamon, mace, nutmeg)  in the GM letters: run the notebook '[1] Looking for opium and spices in the letters.ipynb'
4. Visualisation
   
    3.1. Run the notebook '[2] Tracing commodities in GMs over time - visualising opium vs spice.ipynb' to visualise the appearances of opium and spices in the GM letters (Figure 1 in the abstract)
   
    3.2. Run the notebook 'BKB_commodity_voyages_value.ipynb' to visualise the number of times opium and spices were listed as cargo (Figure 2 in the abstract) and the average value of these products per year according to the BKB dataset (Figure 3 in the abstract)
