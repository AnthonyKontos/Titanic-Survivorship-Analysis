# Titanic-Survivorship-Analysis
Determining which factors made a passanger more likely to survive the Titanic using data analysis in Pandas

## Approach 
I approached my analysis in python using the pandas library almost exclusively. By limiting the analysis to few libraries
and/or functions we can ensure that we are simplifying the data as opposed to making it more complex than it already is in
its raw format. This is crucial as it makes the data easier to interpret and present by and to a layperson audience with
little to no scientific/statistical background.

## Functionalities Used
For basic representationns of the data that did not necessitate new columns, I used pandas' groupby() function. I used this
function in these scenarios because it was the simplest way to properly complete the task. In one case I used min(), max(),
and mean() functions to represent each passengers fare price as simply "high" or "low" as opposed to a numerical value. This
came in handy when determining whether fare price was related to ticket class and whether each of these had a connection to 
survival rate

The most useful function used in this assignment was pd.cut(), which allowed us to sort the data into specified bins and
assign new labels to the columns which enhance clarity. As a result we were able to simplify a bunch of numerical data into
a more presentable manner. This was particualrily useful when determining whether each fare price was 'high' or 'low' 
and when determining which age group each indiviudal belonged to. 
