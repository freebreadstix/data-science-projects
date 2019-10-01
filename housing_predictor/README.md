# Ames Housing Data

## Objective: 

Create a Regression Model to predict housing price based on a house's features. This model will be used to estimate market value based on features of a house, such as number of bedrooms and location, which will be useful for users who are shopping for a house when negotiating price. Performance will be measured by difference between model prediction and actual house price.

### Tasks 
(based on Appendix B from Hands-on Machine Learning w/ SKLearn and TF by Aurelion Geron):

- Program to grab Housing Data from web once [2]
	- Reads housing features from each entry
		- Essential features
	- Read into dataframe
	- Writes into SQL database

- Grab housing posts consistently [3]
    - Accessed cached posts
    - Setup server/system to scrape craigslist

- Identify essential features [1]
    - Cross reference with housing listings to find features commonly recorded in housing sales

- Explore essential features [5]
	- Read about feature online
		- How is it recorded?
		- What does it normally look like?
  - Learn about distribution, % missing, type
  - Study feature correlations
  - Brainstorm other essential features missing

- Clean and prepare essential features [5]
  - [O] Fix outliers
  - Missing values
  - Feature engineering and selection
  - Feature scaling
  
- List Promising Models [1]
  - Run model on data, comparing accuracy scores

- Fine-Tune Model [3]
  - Fine-tune hyperparameters
  - Ensemble Method
  - Make pipeline
  - Test model on test set for final performance
  
- Export model as usable app [10]
  - as website or app
  - allow users to enter only certain features of house and still make prediction
        - output how missing features affect prediction
  
- Gradually roll out less useful features
  - Determine usefulness based on criteria 
  - For each feature
  - Study feature:
        - Name
        - Type
        - % nan
        - Usefulness
        - Distribution
  - Feature correlations
  
  ### Completed
  - Identify target feature
