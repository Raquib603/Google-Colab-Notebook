# This is google Colab for Python/Jupyter_Notebook <br>

--df.loc['Yemen'] ~ only works on proper indexes <br>
--df.iloc[1] ~only integer value input
--df[['Rank', 'Capital']] ~to see the specific columns <br>
--df.sort_values (by = 'Country', ascending = False) ~ sort by any column <br>
--df.columns ~ to see the column names <br>
--df.set_index('Country', inplace = True) ~ we should select a proper column <br>
df.reset_index(inplace=True) ~ For resetting indexes
--df.drop(columns = ['column_name'] ~ for dropping column <br>
--axis 0 = rows and axis 1 = columns<br>
--df[df['Rank'] < 10].sort_values(by = 'Rank', ascending = False) ~ Column with condition <br>
--df[df['Country'].str.contains('United')] ~ to see the specific row with string value <br>
--df2.filter(items =['Continent', 'CCA3'], axis = 1) ~ specific column <br>
--df2.filter(items =['Zimbabwe'], axis = 0) ~ specific row <br>

--frame_group_by = df.groupby('Base Flavor') ~ Grouping on a column
--df.groupby('Base Flavor').count() ~ Group wise other column's count
--frame_group_by.mean(numeric_only=True) ~ Group wise other column's mean
--df.groupby('Base Flavor').agg({'Flavor Rating':['mean','max','count','sum']})
--df.groupby('Base Flavor').sum(numeric_only=True) ~ Group wise other column's summation


#Numpy Visuals
