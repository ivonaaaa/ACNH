# Animal Crossing: New Horizons
> Data analysis project

### Description
This project is all about exploring and analyzing a publicly available dataset from the game **Animal Crossing: New Horizons**. The catalog consists of 30 .csv files, each containing data on in-game items, characters, insects, and other entities. Source of the dataset: https://www.kaggle.com/datasets/jessicali9530/animal-crossing-new-horizons-nookplaza-dataset?resource=download

### Some of the questions explored
- How are NPCs distributed by gender, personality, species and hobbies?
- Which types of items are most common in the catalog?
- How are item prices distributed?
- Which items are the least profitable to resell?
- Are there groups of similar entities based on shared characteristics?
- Are there outliers that significantly differ in availability or price?

### Technologies used
- **Exploratory data analysis (EDA):** Descriptive statistics, histograms, bar plots
- **Basic natural language processing (NLP):** Word frequency analysis of textual attributes
- **Clustering and outlier detection:** K-means, DBSCAN

## Installation and running
Steps to Install the Project:
1. **Clone and open the Repository**:
   Open a terminal (or command prompt on your machine) and run the following commands:

   ```bash
   git clone https://github.com/ivonaaaa/ACNH.git
   ```
   ```bash
   cd ACNH
   ```
2. **Kaggle API setup**:
   This project uses a dataset downloaded from Kaggle, which requires an API token:
   - Log in to your Kaggle account
   - Go to accout -> API -> Create New API Token
   - Save the generated token
3. **Create the kaggle.json locally:**
   - Locate the commented code in the notebook and uncomment it
   - Insert your Kaggle username and API token
   - Run the cell
6. **Place the kaggle.json in the correct location:**
   Put the file anywhere on your machine, but remember to update the path in the notebook accordingly
7. **Run the remaininng configuration cells**:
   Run the remaining configuration cells which will set correct file permissions, download the dataset, unzip the .csv files, ...
   
   
