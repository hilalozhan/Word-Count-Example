# Word Count Example

###  How to count the occurrences of unique words in a text, using basic
map reduce?


Create SparkConf object that contains information about your application and set
App Name as studentNo_studentName.

• Normalize the text:
• Make all text lowercase
• Remove punctuations and digits
• Remove empty lines
• Print number of lines in the file.
• Count (calculate) the occurrences of unique words in a text (key-value).
• Sort the result descending by value. Ex:
('the', 19)
('of', 18)
('was', 13)
('it', 12)
('a', 9)
('were', 6)
('and', 4)
('for', 3)
('to', 3)
('age', 2)

• Save first 10 key-value pair of sorted result as a text file (You may use saveAsTextFile
or any print function for printing results into text file), named it’s directory as
studentNo_output_fileSize, and print these first 10 key-value pair in the Jupyter
notebook. Do NOT print all result.
• Calculate and print execution time of program.

