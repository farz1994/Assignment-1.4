>Read multiple JSON files into a directory to convert into a dataset.
I have files text1, text2, text3 in the directory JSON.

install.packages("rjson")
library("rjson")
result <- fromJSON(file = "input.json")
print(result)

result <- fromJSON(file = "input.json")

js<-'{

"name": null, "release_date_local": null, "title": "3 (2011)",

"opening_weekend_take": 1234, "year": 2011,

"release_date_wide": "2011-09-16", "gross": 59954

}'

Write a script for Variable Binning using R.

Example of BIN creation using cut function in R
x = c(1,10,20,40,70,80)
y = rep(1:80,1)
cut(y,x)

Result : 
Levels: (1,10] (10,20] (20,40] (40,70] (70,80]
