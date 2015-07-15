# synthetic-data-generator
usage:
java -jar TestCaseGen.jar filename numOfCol columnValueRange numOfRows numOfClasses 

example:
java -jar TestCaseGen.jar sample 10 1000 100 2

This will create a file called sample, with 10 columns, 100 rows, 2 classes and the attribute values will approximately be in the range of 0to 1000.
