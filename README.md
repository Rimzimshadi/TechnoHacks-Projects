# TechnoHacks-Projects
These projects are undertaken as internship projects provided by TechnoHacks

Task-1 - Perform Data Cleaning - For #technohacksedutech Data Analyst Internship ✨
During this phase, I worked on cleaning the Titanic dataset using MS-Excel and followed these stepswhile cleaning the columns- 
1. Age - found the average age for all the passengers according to their class and sex. Filled the missing values in the table with these values accordingly.
2. Cabin - Extracted the first initial from this column. Imputed 'M' wherever cabin value was not given
3. Embarked - found the mode and imputed the missing values with this mode.
4. Title - Extracted title from Name column using formula. Combined many of these titles into Royalty category final ones resulting into Mr, Miss, Mrs, Master and Royalty to reduce categorization
5. Ticket - Extracted only the alphabetical part from this using intermediate steps 
6. Created one hot code variables for the categorizations of title, embarked, cabin, ticket columns

⭐ Dataset: Titanic - train
⭐ Data Source: Kaggle
⭐ Tool Utilized: MS-Excel

The numbers in red highlight are the total count of columns which are not null. 
The titles in green highlight show the ones in which columns are fully filled, clean and could be used for further analysis.
The titles in grey highlight are the intermediate steps for the final columns

Task-2 Calculate summary statistics - For #technohacksedutech Data Analyst Internship ✨

During this phase, I engaged with Python functions that are pivotal in the domain of data analysis:
☘ mean() - Calculating the mean of a dataset.
☘ median() - Determining the median value of a dataset.
☘ mode() - Identifying the mode(s) in a dataset.
☘ std() - Computing the standard deviation of a dataset.

I effectively employed these functions to derive essential summary statistics for the designated dataset.
⭐ Dataset: Titanic - train
⭐ Data Source: Kaggle, as recommended by TechnoHacks.
⭐ Tool Utilized: Jupyter Notebook

Task 3- Find and Remove duplicates - For #technohacksedutech Data Analyst Internship ✨

There were no duplicates in the whole dataset, but if one wants to find and remove duplicates from columns, we can do that particular to columns using the following functions-
☘ duplicated() - to find duplicates
☘ drop_duplicates() - to remove duplicates

⭐ Dataset: Iris Species
⭐ Data Source: Kaggle, as recommended by TechnoHacks.
⭐ Tool Utilized: Jupyter Notebook
