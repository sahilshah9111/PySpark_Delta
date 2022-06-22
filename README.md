## PySpark_Delta

### SETUP INSTRUCTIONS:
Well functioning Computer/Laptop, Good internet connection, Google Colab

### EXECUTION INSTRUCTIONS:
1. Download Java package in Google Colab 
2. Next, download and unzip Apache Spark with Hadoop to install it
3. Setup Environment variables for Java, Spark and Delta
4. Then we need to install and import the 'findspark' library that will locate Spark on the system and import it as a regular library.
5. Now, import SparkSession from pyspark.sql and create a SparkSession, which is the entry point to Spark.
6. After we read CSV file provided into spark dataframe. Then I wrote data in dataframe to local file system i delta format.
7. Then, read the data from delta format to dataframe.
8. Finally, record count of dataframe is printed.
