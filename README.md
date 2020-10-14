# Pandas_Challenge
Pandas Homework
Hello, everyone! We're back for another to-the-mat round with coding! My wine consumption is expanding even more with coding than it did in the first months of quarantine. Here we go. 

So this Pandas challenge was just that--challenging, but I also enjoyed it. I feel like I did a lot of work that Pandas didn't like and refused to accept. For instance, I would create a data frame that had things in it that I wanted to reference in another dataframe ("SN_only_purchase_data_bin_counts" and "SN_Data_Purchase_df")...and Pandas would refuse to access the information in Frame1 to display in Frame2. I ended up doing a few janky hacks by merging the tables ("items_df") with "popular_items") instaed of referencing the values in the columns...or by cutting and pasting the code that made Frame1 straight into the column-variable definition in Frame2. (Maybe that's better coding? Jury's out on that).

I'm still having some formatting issues, with my strings of decimal places that are too long and the lack of <$> in front of the money columns. I hope to improve upon this. A few other formatting issues...I tried to make some variables that are currently just <print()>ed into dataframes, but Pandas seemed really reluctant to do that. I have a few #commented notes about this in the actual lines of code. 

Here are some trends visible in this dataset:

Those gamers in the 20-24 age range are the biggest spenders by almost triple the numbers of the next-closest category (the 15-19 age range). It's worth investigating if this is the result of young adults finally having their own credit cards/electronic payment accounts that teenagers do not have. Also, if this is related to young adults not being under parental supervision anymore.

The largest gender demographic represented is males, by a LOT. It's worth investigating if this is accurate to the IRL gender of the players or is a choice represented by women not wishing to be harrassed by presenting as female in an online forum. 

While males are overepresented among this dataset, it's worth noting that female spend more per purchase and on average than males. "Other/Non-Disclosed" is the highest spender of all. It might be suggested to marketing personnel that pursuing the female/other demographic could be more profitable per player than catering to the male players, although, of course, the economies of scale in marketing still belong to males. 