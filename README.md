# Apache-Spark
The Command Prompt displays the Java version installed on the system, which is 1.8.0_431, also known as Java 8. It confirms that Java HotSpot(TM) Client VM is active and running in mixed mode.
![image](https://github.com/user-attachments/assets/94659325-d81d-424c-8bbc-44e171512ded)

The Command Prompt shows Apache Spark version 2.1.1 successfully starting in a local environment. The Spark shell is initialized and ready for use.
![image](https://github.com/user-attachments/assets/8844d3c8-82be-435b-9850-9ea9b2781890)

The Spark shell initializes using Scala 2.11.8 and Java 1.8.0_431, with the user importing SparkSession from org.apache.spark.sql. A SparkSession builder is created successfully.
![image](https://github.com/user-attachments/assets/0be99809-a5a4-4fa0-82c8-4cd5bdba884e)

Loading the Netflix dataset from my C drive
![image](https://github.com/user-attachments/assets/dd96ec48-80af-4034-8109-18e40c839c7b)

Displaying the First few fews to verify the data
![image](https://github.com/user-attachments/assets/9356cc56-5352-44c4-bebb-b558af533c4c)

The netflixData DataFrame schema is printed, showing columns like title, genre, and IMDb score, with their data types. The total number of rows in the dataset is counted and displayed as 583.
![image](https://github.com/user-attachments/assets/03c956ec-074b-4038-9941-3b906e43d8a6)

The netflixData DataFrame is grouped by the "genre" column, and the count of rows for each genre is calculated. The top 20 genres with their counts are displayed, showing the frequency of each genre in the dataset.
![image](https://github.com/user-attachments/assets/5a1b0d43-4152-4554-a156-540e316a8add)

It displays a Scala code snippet that groups Netflix data by year, counts occurrences, and orders the results. The output table shows the year-wise distribution of records from 2014 to 2021.
![image](https://github.com/user-attachments/assets/f412f36a-4a9b-4c5d-8a67-f7470488bb1f)

It shows a Scala code snippet that filters Netflix data for movies in the "Action" genre and displays the first 10 results. The output table includes details such as title, genre, language, IMDb score, premiere date, runtime, and year.
![image](https://github.com/user-attachments/assets/8c653f5a-512b-4fb7-a76d-4ccac028f0c7)

It shows a Scala code snippet that retrieves distinct genres that we can use from a Netflix dataset. The output table lists 20 unique genres, including "Comedy horror," "Thriller," "Romantic comedy," and "Adventure."
![image](https://github.com/user-attachments/assets/3a161ee6-f935-4a31-9fab-b658c1d1ac73)

It shows a Filtered Spark (Scala) table of Netflix movies from 2020 with columns: title, genre, language, IMDB score, premiere, runtime, and year.
![image](https://github.com/user-attachments/assets/dac13b0d-3484-42cf-8af0-19ed44215ae4)

It shows a Spark (Scala) query that groups Netflix data by the "year" column, counts the number of entries, and orders by year. The table displays years from 2014 to 2021 and their corresponding counts.
![image](https://github.com/user-attachments/assets/07c331aa-0b7a-4579-ac11-74e403eef701)
![image](https://github.com/user-attachments/assets/f49e7c7b-cc37-4483-8f07-07319700c3d1)

















