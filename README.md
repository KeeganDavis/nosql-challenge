# nosql-challenge
## Description
The NoSQL_setup_starter notebook imports the data from the establishments json file into MongoDB. Pymongo is used to perform CRUD operations on the database to insert data for the new restaurant, remove restaurants matching a paramater, and update the data type of some of the values. The NoSQL_analysis_starter notebook analyzes the database based on the parameters in the markdown blocks and adds the data to a dataframe.
## Requirements
MongoDB, Pymongo, pandas, and pprint are required for this repository.
## Installation
Clone the repository: git@github.com:KeeganDavis/nosql-challenge.git
## Usage
To use the NoSQL_setup_starter notebook, the json file must be imported into MongoDB first by using `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`. Then select a python kernel and run the code blocks to perform the CRUD operations. To use the NoSQL_analysis_starter, first make sure to run all of the cells in the NoSQL_setup_starter notebook. Then select a python kernel and run the code blocks to perform the analysis.