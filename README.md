# pandas-challenge

Well, lets start this out by saying that this is the 2nd time I have done this challenge. I made the mistake of not pushing this to git after I finished a coding 8 hour banaza,
checkpointed it and saved the jupyter file and 4 am and happily went to bed. I thought that was enough, little did I know it was not to be so. My mistake I believe was in working
on the starter file, and saving it there. Seemed natural enough had the code and was one less tab that I had to have open. I woke up the next day to finish the last half of the activity
as I had gotten to the age count and got it to print. It either didn't save, or my mistake was opening the Heroes Of Pymoli file first and that overwrote it, or when I git pulled, it
it overwrote the file. 

Never again.

Im back to where I started, I added to the analysis beyond what was recommended two columns that I thought were interesting, the most common item and the least common item.

I don't know what did it, but it was certainly difficult to get the first series into a dataframe.

Well figuring out how the sort index worked on the datafrane took a bit of time, but got it working on ascending = true.

Didn't get either the money($) or percent(%) to print to any of the summary tables. Could get the money sign to work after realizing that you have to call it where you would when about to print,
say the summary table. it doesn't go in the pd.DataFrame portion of declaring the column headers. Plus, I had all of the percentages and the dollar amounts already rounded to two decimal places, 
and since the summary table column names tell the reader what the columns are, ie count, percentage, money adding the symbols themselves was just window dressing.