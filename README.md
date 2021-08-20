# Analysis-on-Olympic-dataset-using-HDFS-and-Hive
<img src="https://miro.medium.com/max/981/1*vH0yWboPy9ptgOSqClcS4Q.png" alt="hadoop" width="100" height="40"/> 
<img src="https://www.clipartmax.com/png/middle/435-4359583_apache-hive-logo-hive-hadoop.png" alt="hdfs" width="100" height="40"/>
<br>

   In this project I’m going to perform analysis on Olympic dataset took from kaggle. This dataset contain a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
Dataset contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events). 
The columns are:
1)	ID - Unique number for each athlete
2)	Name - Athlete's name
3)	Sex - M or F
4)	Age - Integer
5)	Height - In centimeters
6)	Weight - In kilograms
7)	Team - Team name
8)	NOC - National Olympic Committee 3-letter code
9)	Games - Year and season
10)	Year - Integer
11)	Season - Summer or Winter
12)	City - Host city
13)	Sport - Sport
14)	Event - Event
15)	Medal - Gold, Silver, Bronze, or NA

For performing analysis I’m going to use Hadoop and Apache Hive as a data warehousing software. Hive gives an SQL-like interface to query data stored in various databases and file system in this project I’m going to use HDFS file system for data storage.
