# pandas-challenge
Most of challenge's idea was taken from class activities from all three weeks.
Also help from AskBCS trainind staff:


#passing_both = school_data_complete[(school_data_complete['maths_score'] >= 50) & (school_data_complete['reading_score'] >= 50)].shape[0]
#percentage_overall_passing = (passing_both / total_students) * 100

Idea of above code was provided by Ask Bcs teaching staff


#per_school_summary.reset_index(inplace=True); #print(per_school_summary.to_string(index=False))
I was stuck on how to get first column and all the data in tabular format, help from stack overflow


Also a through search on the google helped me in doing this challenge.

especially for this; 
# Convert the budget values to dollars
school_data['Total School Budget'] = school_data['budget'].map('${:,.2f}'.format)

# Convert the Per Student Budget in dollars
school_data['Per Student Budget'] = school_data['Per Student Budget'].map('${:,.2f}'.format)
