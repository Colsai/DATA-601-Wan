# Tidy Data Notes

## Notes about df.melt
- df.melt() to melt data into a more-collapsed set of data.   
id_vars = [names]  
df = pd.melt(frame = df, id_vars = id_vars, var_name = "week", value_name = "rank")  


-- Supervised machine learning predicts a label (so a class). 
Does a person have cancer? etc.
We need label training data to do this well. It has to be a known value over time, such as emails and fraud detection. 

- Find a dataset that includes labels  
- Label data by hand ourselves  
- Ask users to label data for us  
- Hire users to label data for you (e.g. Amazon Mechanical Turk, Figure Eight)  
