# Tidy Data Notes

## Notes about df.melt
- df.melt() to melt data into a more-collapsed set of data. 
id_vars = [names]
df = pd.melt(frame = df, id_vars = id_vars, var_name = "week", value_name = "rank")
