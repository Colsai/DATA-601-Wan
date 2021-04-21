# Tidy Data Notes

## Notes about df.melt
- df.melt() to melt data into a more-collapsed set of data.   
id_vars = [names]  
df = pd.melt(frame = df, id_vars = id_vars, var_name = "week", value_name = "rank")  


-- Supervised machine learning predicts a label (so a class). 
Does a person have cancer? etc.
We need label training data to do this well. It has to be a known value over time, such as emails and fraud detection. 
