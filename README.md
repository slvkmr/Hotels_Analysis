## Hotels Analysis

### Input: 
Json file about hotels in India with which has 9 fields and 305 rows.Rows are subjecct to change and the code must scale to size of data. The fields are as below:
- HOTE
- ADDRESS
- STATE
- PHONE
- FAX
- EMAIL ID
- WEBSITE
- TYPE
- Rooms

### Functionality:
The solution must process the json file and form a pandas dataframe by extracting the data. From the dataframe, hotels with maximum of rooms under each type must be computed. Below are possible approaches:
- Naive approach is to fit entire data into the memory and do the computation.
- Increase the number of machines and process the data by distributing among them.
- Divide the data into chunks which could be fit into memory and process the data sequentially.

Submitted solution contains first and third approach. First approach is in the notebook hotels_analysis.ipynb and second approach is in the notebook hotels_analysis_large_files.ipynb

## Output:
The computed output dataframe is stored as csv file. result.csv and result_1.csv files are output files.
