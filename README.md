>Read multiple JSON files into a directory to convert into a dataset.
I have files text1, text2, text3 in the directory JSON.

install.packages("rjson")
library("rjson")
result <- fromJSON(file = "input.json")
print(result)

result <- fromJSON(file = "input.json")
