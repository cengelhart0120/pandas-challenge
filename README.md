# pandas-challenge Readme File
Python code written using Pandas for the completion of Module 4's challenge (homework)

For the most part, the written Python codes were derived from curriculum content, via instruction and/or in-class activities, but there were some sources consulted for completing the challenge (all are also mentioned within the code).

The first mentioned source was found at:
  https://stackoverflow.com/questions/20461165/how-to-convert-index-of-a-pandas-dataframe-into-a-column
The way I decided to tackle the "School Summary" portion of the analysis was to group by both school name and type, but this led to a double-indexed dataframe, so I had to figure out how to reset the dataframe to have only one index, and what I found on the web page was helpful in figuring that out.

The second mentioned source was found at:
  https://stackoverflow.com/questions/11346283/renaming-column-names-in-pandas
I'm not sure if I missed this in class or should have been able to figure it out through similar examples, but I found the above web page useful for renaming the "School Type" column in the School Summary DataFrame.

The final source I mention in the code was found at:
  https://stackoverflow.com/questions/32464280/how-to-convert-currency-column-with-and-to-numbers
To construct the Scores by School Spending DataFrame, I found I had to first convert the dollar amounts (string values) into float values. What I found on that webpage was helpful for doing that.

For more in-depth rationale for specific code/lines of code, please see the code files themselves because they contain comments throughout.
