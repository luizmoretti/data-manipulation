# Processing Data, Pandas
In this repository I will explore the loan data of the collections of the UFRN library system (Federal University of Rio Grande do Norte - Brazil)

Day 1 - consists of downloading csv files from a GitHub repository, reading each csv file, concatenating all files into just one DataFrame, removing DataFrame duplicates 
and null values, read data contained in the instance and merge both DataFrames


Day 2 - In this part of the process I will do the first manipulations of data contained in the DataFrame.
    
   The current DataFrame columns are in Portuguese-Brazil, for a better understanding of the whole process I will first perform a column translation process
 
 - The collection items in a library are organized by a classification system according to the respective theme. There are several systems, but this set is in accordance with the UDC - Universal Decimal Classification. This classification is decimal, as it varies according to the class of each subject:
 
 - 000 to 099: Generalities. Science and knowledge.
 - 100 to 199: Philosophy and psychology.
 - 200 to 299: Religion.
 - 300 to 399: Social sciences.
 - 400 to 499: Vacant class. Temporarily unoccupied.
 - 500 to 599: Mathematics and natural sciences.
 - 600 to 699: Applied sciences.
 - 700 to 799: Fine arts.
 - 800 to 899: Language. Language. Linguistics.
 - 900 to 999: Geography. Biography. History.
